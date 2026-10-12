# line_notify_messages

LINE Notify訊息通知 權杖(Token) 訊息 圖組編號(ID) 貼圖編號(ID)

使用此服務需要先登入 https://notify-bot.line.me 申請權杖(Token)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "line_notify_messages",
  "title": "LINE Notify訊息通知 權杖(Token) 訊息 圖組編號(ID) 貼圖編號(ID)",
  "tooltip": "使用此服務需要先登入 https://notify-bot.line.me 申請權杖(Token)",
  "offeredInToolbox": {
    "ea": false,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": true,
    "mt5script": true
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
      "name": "MESSAGES",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "STKPKGID",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "STKID",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"line_notify_messages\"></block>"
}
```
