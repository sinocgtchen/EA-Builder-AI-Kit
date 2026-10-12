# EA Builder XML 格式規則

## 平台與入口

| 目標 | generatorAvailable 鍵 | 程式入口積木 |
| --- | --- | --- |
| MT4 EA | mt4 | mql4_setup |
| MT5 EA | mt5 | mql4_setup |
| MT4 Script | mt4script | mql4script_setup |
| MT5 Script | mt5script | mql4script_setup |

MT5 EA 也使用 `mql4_setup`，不要發明 `mql5_setup`。EA 執行區為 `OnTick`；Script 骨架在 XML 也使用 `OnTick` 輸入名稱，由 Script 產生器輸出 `OnStart()`。XML 本身不會自動切換網站目標平台，使用者需選擇正確的程式碼頁籤及模式。

## 基本結構

```xml
<xml xmlns="https://developers.google.com/blockly/xml">
  <variables><variable id="lots">Lots</variable></variables>
  <block type="mql4_setup" x="30" y="30">
    <statement name="Declare">
      <block type="variables_declare">
        <field name="TYPE_PARAMETERS">input</field>
        <field name="VAR" id="lots">Lots</field>
        <field name="TYPE">double</field>
        <value name="VALUE">
          <block type="math_number"><field name="NUM">0.01</field></block>
        </value>
      </block>
    </statement>
  </block>
</xml>
```

輸出連接到 `<value name="...">`；敘述連接到 `<statement name="...">`；同一敘述鏈的下一塊積木使用 `<next><block .../></next>`。不要把敘述積木接到 value，或把輸出積木接到 statement。

欄位名稱及下拉值必須使用規格中的識別字，不可使用中文顯示文字代替。例如 EMA 的方法值是 `MODE_EMA`，價格值是 `PRICE_CLOSE`。

所有變數先列在 `<variables>`，使用 `variables_declare` 定義 MQL 型別、初值及是否為 input。各 `<field name="VAR" id="...">` 必須引用同一個 id 與名稱，不可只新增 variables 節點而漏掉宣告積木。

## 形狀與可變輸入

`inputs[].kind` 可為 value、statement 或 dummy；dummy 沒有可接積木的插槽。`fields[].name` 是 field 名稱，兩者不要混用。`connectionChecks: null` 表示沒有型別限制，不代表輸入可以省略。

`defaultXml` 是網站預設積木的序列化形式，可作為起點。if/else、列表及副程式等形狀可能由 `<mutation>` 決定。預設模板只涵蓋預設形狀；需要不同形狀時參考對應範例，不要猜測 mutation。副程式呼叫的參數與宣告必須一致。

XML 內 `&`、`<`、`>` 等需要轉義。日期、顏色及數值欄位需符合網站欄位格式。策略若有未被目前規格支援的功能，應先告知使用者，不要靜默刪除。

## 範例與驗證

範例中的交易參數只是現有專案資料，不要直接沿用到新策略。均線範例原本是 SMA，若使用者指定 EMA，必須改為 `MODE_EMA`。進出場、停損停利及是否平反向單仍要根據使用者回答設定。

最低驗證順序：XML 語法 → 規格中的積木／欄位／輸入 → EA Builder 匯入與工作區連接 → 目標產生器輸出 → MetaEditor 編譯 → 策略測試器回測。不要把可載入 XML 說成可直接實盤交易。
