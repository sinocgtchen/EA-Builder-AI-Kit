# Send_messages_mobile

發送訊息到手機MT4/MT5 訊息

發送訊息到手機MT4/MT5終端,需要到MT4/MT5平台設定ID

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "Send_messages_mobile",
  "title": "發送訊息到手機MT4/MT5 訊息",
  "tooltip": "發送訊息到手機MT4/MT5終端,需要到MT4/MT5平台設定ID",
  "offeredInToolbox": {
    "ea": true,
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"Send_messages_mobile\"></block>"
}
```
