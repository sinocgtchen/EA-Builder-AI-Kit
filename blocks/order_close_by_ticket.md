# order_close_by_ticket

平倉依單號 單號 手數 最大滑點 顏色

針對已下單部位使用單號平倉出場

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "order_close_by_ticket",
  "title": "平倉依單號 單號 手數 最大滑點 顏色",
  "tooltip": "針對已下單部位使用單號平倉出場",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "LOT",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "SLIPPAGE",
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
  "fields": [
    {
      "name": "LOTS_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"order_close_by_ticket\"><field name=\"LOTS_CHECKED\">TRUE</field></block>"
}
```
