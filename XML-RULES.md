# EA Builder XML 格式規則

## 平台與入口

| 目標 | generatorAvailable 鍵 | 程式入口積木 |
| --- | --- | --- |
| MT4 EA | mt4 | mql4_setup |
| MT5 EA | mt5 | mql4_setup |
| MT4 Script | mt4script | mql4script_setup |
| MT5 Script | mt5script | mql4script_setup |

MT5 EA 也使用 `mql4_setup`，不要發明 `mql5_setup`。EA 執行區為 `OnTick`；Script 骨架在 XML 也使用 `OnTick` 輸入名稱，由 Script 產生器輸出 `OnStart()`。XML 本身不會自動切換網站目標平台，使用者需選擇正確的程式碼頁籤及模式。

## 所有新 EA 策略的必要骨架

每份新生成的 EA 策略 XML 都必須從 EA Builder 的預設 EA 骨架加上策略，MT4 EA 與 MT5 EA 皆適用。不得只輸出零散的進出場積木，或省略程式屬性與 MagicNumber。

- 只保留一個 EA 入口 `mql4_setup`，包含參數宣告、初始化 `OnInit` 與主程式 `OnTick` 三個區域。
- 參數宣告 `Declare` 從 `property_info` 開始，保留版權、網站連結、版本與描述；後接 `MagicNumber` 的外部參數宣告，型別為 `int`。
- 版權預設為 `Forex-EABuilder`、連結預設為 `http://www.forex-eabuilder.com`。資料包版本與新 EA 的預設程式版本統一為 `9.42`，不得填入 `9.42.1` 等三段式版號。使用者另有指定時採用合法程式版本；描述可改成使用者策略名稱。
- 骨架的 MagicNumber 初值為 `168`；使用者有指定交易識別碼時，以使用者值取代初值，保留變數名稱 `MagicNumber`，不得另宣告一個重複的識別碼。交易與持倉篩選引用同一個變數。
- 其他外部參數與全域變數接在 MagicNumber 宣告後的 `next` 鏈。需要啟動時設定的積木放在 `OnInit`，訊號判斷、持倉管理與進出場放在 `OnTick`。
- 未使用的初始化或主程式區可為空，但必須保留 EA 入口及其三區結構。Blockly 重新序列化時可能省略空的 statement 節點，入口仍會顯示空插槽。
- 修改既有策略時，在既有骨架上增修，保留使用者原有屬性、版本、識別碼與其他未要求修改的設定。

Script 使用前述 Script 入口，不套用 EA 的事件區名稱。

## 基本骨架範例

```xml
<xml xmlns="https://developers.google.com/blockly/xml">
  <variables><variable id="input-magic-number">MagicNumber</variable></variables>
  <block type="mql4_setup" x="30" y="30">
    <statement name="Declare">
      <block type="property_info">
        <value name="COPYRIGHT"><block type="text"><field name="TEXT">Forex-EABuilder</field></block></value>
        <value name="LINK"><block type="text"><field name="TEXT">http://www.forex-eabuilder.com</field></block></value>
        <value name="VERSOIN"><block type="text"><field name="TEXT">9.42</field></block></value>
        <value name="DESCRIPTION"><block type="text"><field name="TEXT">My expert advisor</field></block></value>
        <next>
          <block type="variables_declare">
            <field name="TYPE_PARAMETERS">input</field>
            <field name="VAR" id="input-magic-number">MagicNumber</field>
            <field name="TYPE">int</field>
            <value name="VALUE"><block type="math_number"><field name="NUM">168</field></block></value>
          </block>
        </next>
      </block>
    </statement>
    <statement name="OnInit"></statement>
    <statement name="OnTick"></statement>
  </block>
</xml>
```

程式屬性的版本輸入名稱在現有規格中是 `VERSOIN`，須使用此精確名稱，不能自行改成 `VERSION`。MT4／MT5 的 `blank-*-ea.xml` 範例提供相同必要骨架，預設程式版本為 `9.42`。

## 程式版本與 MT5 編譯警告

`property_info` 的 `VERSOIN` 會輸出為 MQL 的 `#property version`，代表這個 EA／Script 的程式版本。本資料包版本與新 EA 的預設程式版本統一設定為 `9.42`。

- 版本使用一個小數點分隔的兩段數字，例如 `1.00`、`1.01`、`2.10`。本資料包檢查兩段各為 1 至 3 位數字。
- 不使用 `9.42.1`、`v1.00`、日期或帶說明文字的版號。MQL5 的 Market 版本格式警告要求 `xxx.yyy`；`9.42.1` 有兩個小數點，不符合此格式。
- 新策略未指定程式版本時使用 `9.42`；使用者指定值不符合格式時，說明問題並請其指定有效程式版本，不自行截斷或換算三段式版本。
- 修正這類警告時，只修改程式屬性中的版本文字，不調整交易條件、手數、持倉限制或 MagicNumber。修改既有 XML 但本次無關版本時，若發現不符合格式的版號，列出警告，不靜默改版。
- `ai-kit/VERSION` 與 `blocks-reference.json` 的 `productVersion` 都為 `9.42`，產生腳本從同一個版本檔讀取新 EA 的預設版號。`sourceProductVersion` 另記錄產生規格所用的 EA Builder 主專案版本，主專案 `VERSION` 不受本次資料包版號調整影響。

來源：[MQL5 程式屬性文件](https://www.mql5.com/en/docs/basis/preprosessor/compilation)、[MQL5 編譯警告清單](https://www.mql5.com/en/docs/constants/errorswarnings/warningscompile)。

輸出連接到 `<value name="...">`；敘述連接到 `<statement name="...">`；同一敘述鏈的下一塊積木使用 `<next><block .../></next>`。不要把敘述積木接到 value，或把輸出積木接到 statement。

欄位名稱及下拉值必須使用規格中的識別字，不可使用中文顯示文字代替。例如 EMA 的方法值是 `MODE_EMA`，價格值是 `PRICE_CLOSE`。

所有變數先列在 `<variables>`，使用 `variables_declare` 定義 MQL 型別、初值及是否為 input。各 `<field name="VAR" id="...">` 必須引用同一個 id 與名稱，不可只新增 variables 節點而漏掉宣告積木。

## 指標先賦值，判斷式使用變數

為了讓使用者容易閱讀，優先把指標積木放在獨立的賦值積木中，再以短小的變數積木組合進出場條件，避免把完整指標及其商品、週期、參數反覆塞進判斷式。

- 指標計算值使用 `variables_declare` 宣告為一般變數（`TYPE_PARAMETERS=general`），一般指標數值使用 `double`。它們是執行時取得的資料，不宣告成不可更新的外部輸入參數。指標週期、門檻與手數等使用者可調設定，才依需求宣告為 `input`。
- 使用 `variables_set` 的 `VALUE` 接指標積木，將結果存入具名變數；判斷式改接 `variables_get`。先更新指標值，再執行依賴該值的比較與交易邏輯。
- 變數名稱需能區分指標、用途與資料時點，必要時加中文註解。均線交叉可用四個值：短期均線最近收盤值、短期均線前一根收盤值、長期均線最近收盤值、長期均線前一根收盤值。
- 相同指標、商品、時間週期、設定、輸出線與 K 棒時點，在同一次訊號評估中優先計算一次並重用。不同週期、不同輸出線或不同 K 棒時點不可共用成同一個值，以免改變交叉與多週期邏輯。
- 依原策略的報價或新 K 棒判定時機更新，不因抽成變數而改變訊號時點。只在初始化區設定一次指標值，會使後續值過期，因此不可這樣替代執行時更新；MT5 指標控制代碼的初始化與指標數值的更新也要區分。
- 資料不足或指標讀取失敗時，不可把變數初始值或上一次留下的值當成本次有效訊號。依原策略處理，沒有另行指定時跳過依賴該指標的訊號評估並說明此行為。
- 不要求每個簡單常數都拆成變數；主要整理較長、重複或不容易看懂的指標積木。修改既有 XML 時保留交易語意與使用者指定的判定時機。

一般文字範例：先取得兩條均線各自最近與前一根收盤的值，再用這四個短變數判斷「短期均線向上交叉長期均線」，不用在每個比較位置重新放入完整均線積木。

## 形狀與可變輸入

`inputs[].kind` 可為 value、statement 或 dummy；dummy 沒有可接積木的插槽。`fields[].name` 是 field 名稱，兩者不要混用。`connectionChecks: null` 表示沒有型別限制，不代表輸入可以省略。

`defaultXml` 是網站預設積木的序列化形式，可作為起點。if/else、列表及副程式等形狀可能由 `<mutation>` 決定。預設模板只涵蓋預設形狀；需要不同形狀時參考對應範例，不要猜測 mutation。副程式呼叫的參數與宣告必須一致。

XML 內 `&`、`<`、`>` 等需要轉義。日期、顏色及數值欄位需符合網站欄位格式。策略若有未被目前規格支援的功能，應先告知使用者，不要靜默刪除。

## 範例與驗證

範例中的交易參數只是現有專案資料，不要直接沿用到新策略。均線範例原本是 SMA，若使用者指定 EMA，必須改為 `MODE_EMA`。進出場、停損停利及是否平反向單仍要根據使用者回答設定。

最低驗證順序：XML 語法 → 規格中的積木／欄位／輸入 → EA Builder 匯入與工作區連接 → 目標產生器輸出 → MetaEditor 編譯 → 策略測試器回測。不要把可載入 XML 說成可直接實盤交易。
