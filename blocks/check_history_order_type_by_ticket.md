# check_history_order_type_by_ticket

是否 歷史交易單號 為 下單方式

檢查歷史交易下單方式

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_history_order_type_by_ticket",
  "title": "是否 歷史交易單號 為 下單方式",
  "tooltip": "檢查歷史交易下單方式",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "ORDER_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "BUY",
          "value": "0"
        },
        {
          "label": "SELL",
          "value": "1"
        },
        {
          "label": "BUY LIMIT",
          "value": "2"
        },
        {
          "label": "SELL LIMIT",
          "value": "3"
        },
        {
          "label": "BUY STOP",
          "value": "4"
        },
        {
          "label": "SELL STOP",
          "value": "5"
        },
        {
          "label": "BUY STOP LIMIT(MT5)",
          "value": "6"
        },
        {
          "label": "SELL STOP LIMIT(MT5)",
          "value": "7"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_history_order_type_by_ticket\"><field name=\"ORDER_TYPE\">0</field></block>"
}
```
