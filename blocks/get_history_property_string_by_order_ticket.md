# get_history_property_string_by_order_ticket

(MT5)訂單號取歷史交易.訂單資料(string) 訂單單號 型別

取得歷史交易資料,資料型別字串(string)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_string_by_order_ticket",
  "title": "(MT5)訂單號取歷史交易.訂單資料(string) 訂單單號 型別",
  "tooltip": "取得歷史交易資料,資料型別字串(string)",
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
    }
  ],
  "fields": [
    {
      "name": "HISTORY_STRING_INFO",
      "value": "ORDER_SYMBOL",
      "kind": "dropdown",
      "options": [
        {
          "label": "商品",
          "value": "ORDER_SYMBOL"
        },
        {
          "label": "註解",
          "value": "ORDER_COMMENT"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_string_by_order_ticket\"><field name=\"HISTORY_STRING_INFO\">ORDER_SYMBOL</field></block>"
}
```
