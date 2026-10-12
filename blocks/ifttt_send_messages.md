# ifttt_send_messages

IFTTT發送訊息 雲端服務 KEY(授權碼) Event Name(事件名稱) 數值1 數值2 數值3

發送訊息到IFTTT雲端伺服器(https://maker.ifttt.com)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "ifttt_send_messages",
  "title": "IFTTT發送訊息 雲端服務 KEY(授權碼) Event Name(事件名稱) 數值1 數值2 數值3",
  "tooltip": "發送訊息到IFTTT雲端伺服器(https://maker.ifttt.com)",
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
      "name": "KEY",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "EVENT",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "VALUE1",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "VALUE2",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "VALUE3",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"ifttt_send_messages\"></block>"
}
```
