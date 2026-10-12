# history_order_type

(MT5)歷史訂單方式

歷史訂單方式

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_order_type",
  "title": "(MT5)歷史訂單方式",
  "tooltip": "歷史訂單方式",
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
    }
  ],
  "fields": [
    {
      "name": "ORDER_TYPE",
      "value": "ORDER_TYPE_BUY",
      "kind": "dropdown",
      "options": [
        {
          "label": "BUY",
          "value": "ORDER_TYPE_BUY"
        },
        {
          "label": "SELL",
          "value": "ORDER_TYPE_SELL"
        },
        {
          "label": "BUY LIMIT",
          "value": "ORDER_TYPE_BUY_LIMIT"
        },
        {
          "label": "SELL LIMIT",
          "value": "ORDER_TYPE_SELL_LIMIT"
        },
        {
          "label": "BUY STOP",
          "value": "ORDER_TYPE_BUY_STOP"
        },
        {
          "label": "SELL STOP",
          "value": "ORDER_TYPE_SELL_STOP"
        },
        {
          "label": "BUY STOP LIMIT",
          "value": "ORDER_TYPE_BUY_STOP_LIMIT"
        },
        {
          "label": "SELL STOP LIMIT",
          "value": "ORDER_TYPE_SELL_STOP_LIMIT"
        },
        {
          "label": "CLOSE BY",
          "value": "ORDER_TYPE_CLOSE_BY"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_order_type\"><field name=\"ORDER_TYPE\">ORDER_TYPE_BUY</field></block>"
}
```
