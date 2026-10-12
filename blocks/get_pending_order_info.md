# get_pending_order_info

取得商品掛單資料(double) 商品 魔術數字 掛單方式 型別

取得商品掛單資料(Buy Limit/Sell Limit/Buy Stop/ Sell Stop/Buy Stop Limit/Sell Stop Limit)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_pending_order_info",
  "title": "取得商品掛單資料(double) 商品 魔術數字 掛單方式 型別",
  "tooltip": "取得商品掛單資料(Buy Limit/Sell Limit/Buy Stop/ Sell Stop/Buy Stop Limit/Sell Stop Limit)",
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
      "name": "PENDING_ORDER_TYPE",
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
    },
    {
      "name": "PENDING_ORDER_INFO",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "手數",
          "value": "0"
        },
        {
          "label": "魔術數字",
          "value": "1"
        },
        {
          "label": "下單價格",
          "value": "2"
        },
        {
          "label": "停損價格",
          "value": "3"
        },
        {
          "label": "停利價格",
          "value": "4"
        },
        {
          "label": "筆數",
          "value": "5"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_pending_order_info\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"PENDING_ORDER_TYPE\">0</field><field name=\"PENDING_ORDER_INFO\">0</field></block>"
}
```
