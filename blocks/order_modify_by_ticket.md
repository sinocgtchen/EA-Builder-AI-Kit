# order_modify_by_ticket

修改停損停利 單號 停損 停利 顏色

依照市場價格(多單:ask, 空單:bid)修改部位的停損價格及停利價格

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "order_modify_by_ticket",
  "title": "修改停損停利 單號 停損 停利 顏色",
  "tooltip": "依照市場價格(多單:ask, 空單:bid)修改部位的停損價格及停利價格",
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
      "name": "STOP_LOSS",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "TAKE_PROFIT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
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
      "name": "SL_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "TP_CHECKED",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"order_modify_by_ticket\"><field name=\"SL_CHECKED\">TRUE</field><field name=\"TP_CHECKED\">TRUE</field></block>"
}
```
