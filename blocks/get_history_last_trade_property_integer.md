# get_history_last_trade_property_integer

取得 (MT4)最後一筆歷史交易 (long) 商品 魔術數字 型別

取得最後一筆歷史交易long資料

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_last_trade_property_integer",
  "title": "取得 (MT4)最後一筆歷史交易 (long) 商品 魔術數字 型別",
  "tooltip": "取得最後一筆歷史交易long資料",
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
      "name": "HISTORY_INTEGER_INFO",
      "value": "DEAL_TICKET",
      "kind": "dropdown",
      "options": [
        {
          "label": "成交單號",
          "value": "DEAL_TICKET"
        },
        {
          "label": "交易時間",
          "value": "DEAL_TIME"
        },
        {
          "label": "魔術數字",
          "value": "DEAL_MAGIC"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_last_trade_property_integer\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"HISTORY_INTEGER_INFO\">DEAL_TICKET</field></block>"
}
```
