# EA Builder AI 積木資料包

這個資料包讓你使用自己的 ChatGPT 產生 EA Builder XML，不需要網站內建 AI 對話框或 API Key。

## 不下載資料包：使用 GitHub 連結

公開 repository：[sinocgtchen/EA-Builder-AI-Kit](https://github.com/sinocgtchen/EA-Builder-AI-Kit)。

在自己的 ChatGPT 貼上以下內容，再填入策略：

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

## 使用步驟

1. 解壓縮 `EA-Builder-AI-Kit.zip`。
2. 在自己的 ChatGPT 開啟新對話，附加 `blocks-reference.json`、`XML-RULES.md` 與 `examples/` 內相近的範例。若無法附加 XML，請使用相同內容的 `.xml.txt` 檔案。
3. 複製 `PROMPT-zh-hant.txt` 全文到對話，再填入策略。
4. 先回答平台、訊號時機、進出場、手數與持倉處理等問題，確認策略摘要。
5. 請 ChatGPT 產生 `strategy.xml`。若沒有下載檔案，將 XML 文字存成 UTF-8 的 `.xml`，不要把 Markdown 的 ``` 標記存進檔案。
6. 開啟 EA Builder 首頁，用「載入積木程式」匯入 XML，選擇正確的 MT4／MT5、EA／Script 模式。
7. 檢查積木與生成的程式碼，使用 MetaEditor 編譯及策略測試器回測。

ChatGPT 的檔案功能依帳號與當時可用功能而定。不能只說「生成 Blockly XML」：EA Builder 的自訂積木類型與輸入名稱必須來自本包規格。

## 檔案內容

- `blocks-reference.json`：從網站實際使用的壓縮積木及四種 MQL 產生器讀取的精確規格。包含欄位、選項、輸入、連接與預設 XML。
- `XML-RULES.md`：變數、value／statement／next、mutation 及平台規則。
- `PROMPT-zh-hant.txt`：可複製給 ChatGPT 的指示。
- `examples/blank-mt4-ea.xml`、`blank-mt5-ea.xml`：EA 骨架。
- `examples/blank-mt4-script.xml`、`blank-mt5-script.xml`：Script 骨架。
- `examples/ma-cross-reference.xml`、`examples/rsi-reference.xml`：既有範例，用來參考結構；不是對你的交易需求或參數的建議。

`generatorAvailable` 只表示目前有該產生器函式，並不保證所有欄位組合都可編譯。`defaultXml` 是預設形狀，不代表必要輸入已填妥。產生的策略必須另外驗證。

本包版本與網站更新後請使用新的資料包，避免舊規格與目前積木不一致。不要附加券商登入資料、帳戶密碼或 API Key。
