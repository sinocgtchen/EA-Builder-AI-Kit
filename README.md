# EA Builder AI 積木資料包

這個資料包讓你使用自己的 ChatGPT 產生積木EA程式(XML)，不需要網站內建 AI 對話框或 API Key。

所有新 EA 策略都必須在預設 EA 骨架上增加積木，保留程式屬性、MagicNumber 外部參數、參數宣告、初始化及主程式三區。具體規則與骨架見 [XML-RULES.md](XML-RULES.md)；MT4／MT5 空白 EA 範例已包含這些必要項目。

目前資料包版本與新 EA 的預設程式版本統一為 **`9.42`**，由本資料包的 `VERSION` 檔維護。不要將 `9.42.1` 填入程式屬性，否則 MT5 會出現 Market 版本格式警告；詳見 XML 規則中的程式版本說明。

為了縮短判斷式積木，生成策略時優先先把指標值存入一般變數，再用變數積木比較。指標值依原訊號時機更新，最近收盤與前一根收盤等不同資料分開保存；指標期數等可調設定仍保留為外部參數。

## 先選擇使用方式

| 方式 | 要準備什麼 | 適合情況 |
| --- | --- | --- |
| 方式一：貼上 GitHub 連結 | 下方指示文字、策略需求；修改舊策略時另附原始 XML | 對話能讀取網頁，想直接使用公開資料包 |
| 方式二：下載資料包並附加檔案 | 解壓縮後的規格、規則、範例與提示詞 | 不使用 GitHub 連結、網頁讀取失敗，或要自行編輯本機提示詞與策略 |

兩種方式擇一即可。這裡的「修改策略」是修改 EA Builder 匯出的積木 XML；下載參考資料包本身不會自動修改你的 EA。

## 方式一：在 ChatGPT 對話框貼上 GitHub 連結

公開 repository：[sinocgtchen/EA-Builder-AI-Kit](https://github.com/sinocgtchen/EA-Builder-AI-Kit)。

### 1. 複製指示與網址，一起貼入對話框

1. 開啟自己的 ChatGPT，建立新對話。
2. 複製下方文字區塊的**全部內容**，包含指示、完整 `https://` 網址及策略欄位。在 Windows 可選取後按 `Ctrl + C`，點進 ChatGPT 訊息輸入框，再按 `Ctrl + V`。
3. 將 `[填入策略]` 替換為自己的需求，至少說明 MT4／MT5、EA／Script、訊號時機、進出場、手數、停損停利及持倉處理，再送出。
4. 請 ChatGPT 先列出實際讀取的規則與積木來源；若回覆無法讀取必要連結，改用方式二。

不要只貼 GitHub 專案首頁網址，也不要只貼本機檔案路徑。下方的 `raw.githubusercontent.com` 是文件的純文字網址，請完整保留。

```text
請開啟並閱讀以下 EA Builder 策略入口及它連結的指示、XML 規則。
依我的策略挑選積木，讀取各積木的精確規格與相近 XML 範例，
先確認缺少的交易規則，再產生 EA Builder 可載入的 strategy.xml。
如果無法讀取任何必要連結，請告訴我，不要猜測或聲稱已讀取。

https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/START-HERE.md

我的交易策略：
[填入策略]
```

貼網址是在提供參考來源，不是把整個 GitHub 自動附加成對話知識。此方式需要該對話有可用的網頁讀取功能，而且必須能讀取 GitHub 內容。若讀取受限，改貼相關積木頁面內容，或使用下方下載／附加檔案方式。網站無需呼叫 OpenAI API。

`BLOCKS-INDEX.md` 提供全部積木索引；`blocks/` 每種積木各一頁，避免必須整份讀取大型 JSON。完整規格仍保留在 `blocks-reference.json`。

### 2. 使用完整策略表單，或修改既有策略

想用表單填寫需求，可開啟 [繁體中文策略輸入範本](STRATEGY-TEMPLATE-zh-hant.md)，只複製「可直接貼上的範本」文字區塊到 ChatGPT，填好後送出。範本已含 GitHub 讀取指示，交易距離使用 points；不必再重複貼上一段啟動指示。

若要修改既有 EA，先從 EA Builder 下載原始積木 `.xml`，在同一對話附加該檔案，再貼上：

```text
請依前面已讀取的 EA Builder 積木規格，修改我附加的原始 XML。
平台與模式：[例如 MT5 EA]
修改需求：[逐項寫出要變更的條件、參數或功能]
保留未要求變更的策略、程式屬性、MagicNumber 與外部參數。
先列出修改摘要及需要確認的問題，確認後提供完整的 strategy-modified.xml。
若無法讀取原始 XML 或必要規格，請列出缺少的資料，不要猜測。
```

只有 `.mq4`／`.mq5` 程式碼不足以保留原本的積木連接，修改積木時請提供 EA Builder 匯出的 XML。

## 方式二：不使用 GitHub 連結，自行下載與修改

### 1. 下載並解壓縮資料包

1. 從 [EA Builder 網站下載資料包 ZIP](https://forex-eabuilder.com/wp-content/themes/storefront/eabuilder_codex_release/downloads/EA-Builder-AI-Kit.zip)，儲存到自己的電腦。
2. 在 Windows 對 `EA-Builder-AI-Kit.zip` 按右鍵，選擇「全部解壓縮」，再開啟解壓縮後的 `EA-Builder-AI-Kit` 資料夾。
3. 保留一份原始資料包，另複製一份作為自己的工作副本。請編輯解壓縮後的檔案，不要直接在 ZIP 預覽內修改。

這個方式不需要開啟 GitHub，也不需要把 GitHub 網址貼進 ChatGPT；仍需使用 ChatGPT 對話服務。

### 2. 附加本機參考檔案並貼上提示詞

1. 在 ChatGPT 建立新對話，使用訊息輸入框旁的檔案附加功能，選取下列解壓縮檔案；按鈕名稱與可用功能依你的介面為準。
   - `blocks-reference.json`：完整積木規格。
   - `XML-RULES.md`：XML 連接與必要骨架規則。
   - `examples/` 中對應平台與模式的空白骨架，必要時加上相近策略範例。
   - 若修改舊策略，另附自己的原始積木 XML。
2. 若無法附加 XML，使用包內相同內容的 `.xml.txt` 範例；自己的 XML 可另存一份 `.xml.txt`。若某種參考檔案無法附加，可改為分段貼上文字，標明檔名；請 ChatGPT 確認所需資料已收到，再繼續。
3. 用文字編輯器開啟本機 `PROMPT-zh-hant.txt`，按 `Ctrl + A`、`Ctrl + C`，再到 ChatGPT 訊息輸入框按 `Ctrl + V`。替換末尾的 `[在這裡填入策略規則]`，送出前補上以下說明：

```text
本次只使用我附加或貼上的本機資料包，不使用 GitHub 連結。
請先確認已收到 blocks-reference.json、XML-RULES.md 與對應平台範例。
若還缺少必要規格或檔案，請列出檔名，等我補齊再生成。
若我附加原始策略 XML，請在它上面修改，保留未要求變更的內容。
我的修改需求：[新建策略填「新建」；修改舊策略請列出具體變更]
```

不需要再貼 `START-HERE.md` 的 GitHub 連結。若改用 `STRATEGY-TEMPLATE-zh-hant.md` 表單，先將表單開頭的 GitHub 網址與讀取指示整段替換成上方「只使用本機資料包」說明，再填寫策略欄位並貼入對話；避免表單仍要求讀取網路資料。

### 3. 自行修改本機資料包或策略

- **調整對話指示或預設需求**：在工作副本中編輯 `PROMPT-zh-hant.txt` 或 `STRATEGY-TEMPLATE-zh-hant.md`，以 UTF-8 儲存，再把修改後的文字貼入 ChatGPT。修改本機副本不會更新 GitHub 或網站下載包。
- **調整 EA 策略**：附加原始 XML 並描述變更，取得完整新 XML；也可在 EA Builder 載入 XML 後自行拖曳、修改積木，再重新下載 XML 保存。
- **修改參考規格前先確認來源**：`blocks-reference.json` 與 `blocks/` 描述網站實際積木。只修改這些文件不會在網站新增積木或改變產生器；一般策略使用者應保留原規格，避免生成網站不支援的 XML。

## 兩種方式完成後：儲存、載入與驗證 XML

1. 回答缺少的交易規則，依所用提示詞確認策略摘要；完整表單允許需求完整時直接生成。
2. 下載 ChatGPT 產生的 `strategy.xml` 或 `strategy-modified.xml`。若沒有下載檔案，將完整 XML 文字存成 UTF-8 的 `.xml`，不要把 Markdown 的 ``` 標記存進檔案；在 Windows 確認檔名沒有變成 `.xml.txt`。
3. 開啟 EA Builder 首頁，用「載入積木程式」匯入 XML，選擇正確的 MT4／MT5、EA／Script 模式。先另存原策略，再載入新檔。
4. 檢查積木與生成的程式碼，使用 MetaEditor 編譯及策略測試器回測。若報錯，將錯誤文字、平台與目前 XML 附回同一對話，請 ChatGPT 依本次資料包規格修正。

ChatGPT 的檔案功能依帳號與當時可用功能而定。不能只說「生成 Blockly XML」：EA Builder 的自訂積木類型與輸入名稱必須來自本包規格。

ChatGPT 功能操作可參考官方文件：[使用 ChatGPT 與檔案](https://learn.chatgpt.com/docs/use-chatgpt)、[網頁搜尋](https://learn.chatgpt.com/docs/web-search)。能使用搜尋不代表每個 GitHub 連結都一定可讀取，仍以該次對話實際讀取結果為準。

## 檔案內容

- `blocks-reference.json`：從網站實際使用的壓縮積木及四種 MQL 產生器讀取的精確規格。包含欄位、選項、輸入、連接與預設 XML。
- `XML-RULES.md`：變數、value／statement／next、mutation 及平台規則。
- `PROMPT-zh-hant.txt`：可複製給 ChatGPT 的指示。
- `STRATEGY-TEMPLATE-zh-hant.md`：一般中文策略表單、points 距離單位與完整填寫示例；已包含 GitHub 讀取指示。
- `examples/blank-mt4-ea.xml`、`blank-mt5-ea.xml`：EA 骨架。
- `examples/blank-mt4-script.xml`、`blank-mt5-script.xml`：Script 骨架。
- `examples/ma-cross-reference.xml`、`examples/rsi-reference.xml`：既有範例，用來參考結構；不是對你的交易需求或參數的建議。

`generatorAvailable` 只表示目前有該產生器函式，並不保證所有欄位組合都可編譯。`defaultXml` 是預設形狀，不代表必要輸入已填妥。產生的策略必須另外驗證。

本包版本與網站更新後請使用新的資料包，避免舊規格與目前積木不一致。不要附加券商登入資料、帳戶密碼或 API Key。
