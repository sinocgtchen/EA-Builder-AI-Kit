# get_history_property_double_by_ticket

(MT4)取得歷史交易資料(double) 歷史交易單號 型別

取得歷史交易資料,資料型別小數(double)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_double_by_ticket",
  "title": "(MT4)取得歷史交易資料(double) 歷史交易單號 型別",
  "tooltip": "取得歷史交易資料,資料型別小數(double)",
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
    }
  ],
  "fields": [
    {
      "name": "HISTORY_DOUBLE_INFO",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "手數",
          "value": "0"
        },
        {
          "label": "下單價格",
          "value": "1"
        },
        {
          "label": "停損價格",
          "value": "2"
        },
        {
          "label": "停利價格",
          "value": "3"
        },
        {
          "label": "平倉價格",
          "value": "4"
        },
        {
          "label": "利息",
          "value": "5"
        },
        {
          "label": "利潤",
          "value": "6"
        },
        {
          "label": "手續費",
          "value": "7"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_double_by_ticket\"><field name=\"HISTORY_DOUBLE_INFO\">0</field></block>"
}
```
