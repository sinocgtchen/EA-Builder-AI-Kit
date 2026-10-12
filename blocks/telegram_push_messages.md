# telegram_push_messages

Telegram 推播訊息 Token(權杖) Chat ID 訊息

在telegram app 上面私訊 @BotFather 輸入 /newbot 他將會請您依序輸入bot顯示名稱及bot的username(必需為bot結尾),完成後可以取得Token(格式類似 12345678:DDSSw-AAGGTE3)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "telegram_push_messages",
  "title": "Telegram 推播訊息 Token(權杖) Chat ID 訊息",
  "tooltip": "在telegram app 上面私訊 @BotFather 輸入 /newbot 他將會請您依序輸入bot顯示名稱及bot的username(必需為bot結尾),完成後可以取得Token(格式類似 12345678:DDSSw-AAGGTE3)",
  "offeredInToolbox": {
    "ea": true,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": false,
    "mt5script": false
  },
  "inputs": [
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "TOKEN",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "CHATID",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "MESSAGES",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"telegram_push_messages\"></block>"
}
```
