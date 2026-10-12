# linebot_messages

LINE Notify訊息通知 權杖(Token) 使用者編號(User ID) 訊息

使用此服務需要先登入 https://notify-bot.line.me 申請權杖(Token)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "linebot_messages",
  "title": "LINE Notify訊息通知 權杖(Token) 使用者編號(User ID) 訊息",
  "tooltip": "使用此服務需要先登入 https://notify-bot.line.me 申請權杖(Token)",
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
      "name": "USER_ID",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"linebot_messages\"></block>"
}
```
