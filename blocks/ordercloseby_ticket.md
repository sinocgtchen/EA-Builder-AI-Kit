# ordercloseby_ticket

透過相反持倉來平倉(OrderCloseBy) 單號 1 單號 2 顏色

透過另一個已進場的相反Buy/Sell單來平倉

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "ordercloseby_ticket",
  "title": "透過相反持倉來平倉(OrderCloseBy) 單號 1 單號 2 顏色",
  "tooltip": "透過另一個已進場的相反Buy/Sell單來平倉",
  "offeredInToolbox": {
    "ea": true,
    "script": true
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
      "name": "ORDER_TICKET",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "OPPOSITE_TICKET",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"ordercloseby_ticket\"></block>"
}
```
