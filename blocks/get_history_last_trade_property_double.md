# get_history_last_trade_property_double

取得 (MT4)最後一筆歷史交易 (double) 商品 魔術數字 型別

取得最後一筆歷史交易double資料

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_last_trade_property_double",
  "title": "取得 (MT4)最後一筆歷史交易 (double) 商品 魔術數字 型別",
  "tooltip": "取得最後一筆歷史交易double資料",
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
      "name": "HISTORY_DOUBLE_INFO",
      "value": "DEAL_VOLUME",
      "kind": "dropdown",
      "options": [
        {
          "label": "成交量",
          "value": "DEAL_VOLUME"
        },
        {
          "label": "成交價格",
          "value": "DEAL_PRICE"
        },
        {
          "label": "手續費",
          "value": "DEAL_COMMISSION"
        },
        {
          "label": "利息",
          "value": "DEAL_SWAP"
        },
        {
          "label": "利潤",
          "value": "DEAL_PROFIT"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_last_trade_property_double\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"HISTORY_DOUBLE_INFO\">DEAL_VOLUME</field></block>"
}
```
