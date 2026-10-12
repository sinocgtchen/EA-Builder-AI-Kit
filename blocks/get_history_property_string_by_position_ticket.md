# get_history_property_string_by_position_ticket

(MT5)持倉號取歷史交易.持倉資料(string) 持倉單號 型別

取得歷史交易資料,資料型別字串(string)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_string_by_position_ticket",
  "title": "(MT5)持倉號取歷史交易.持倉資料(string) 持倉單號 型別",
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
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "下單註解",
          "value": "0"
        },
        {
          "label": "平倉註解",
          "value": "1"
        },
        {
          "label": "商品名稱",
          "value": "2"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_string_by_position_ticket\"><field name=\"HISTORY_STRING_INFO\">0</field></block>"
}
```
