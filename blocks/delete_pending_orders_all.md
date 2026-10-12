# delete_pending_orders_all

依掛單方式刪除所有掛單 商品 魔術數字 掛單方式 顏色

依掛單方式刪除所有掛單

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "delete_pending_orders_all",
  "title": "依掛單方式刪除所有掛單 商品 魔術數字 掛單方式 顏色",
  "tooltip": "依掛單方式刪除所有掛單",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "CURRENCY_PAIR",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "MAGIC_NUMBER",
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
      "name": "",
      "kind": "dummy",
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
      "name": "SYMBOL_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "MAGIC_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "TYPE_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "DELETE_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "BUY LIMIT",
          "value": "0"
        },
        {
          "label": "SELL LIMIT",
          "value": "1"
        },
        {
          "label": "BUY STOP",
          "value": "2"
        },
        {
          "label": "SELL STOP",
          "value": "3"
        },
        {
          "label": "BUY STOP LIMIT(MT5)",
          "value": "4"
        },
        {
          "label": "SELL STOP LIMIT(MT5)",
          "value": "5"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"delete_pending_orders_all\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"TYPE_CHECKED\">TRUE</field><field name=\"DELETE_TYPE\">0</field></block>"
}
```
