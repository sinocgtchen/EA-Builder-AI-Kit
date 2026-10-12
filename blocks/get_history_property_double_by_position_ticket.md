# get_history_property_double_by_position_ticket

(MT5)持倉號取歷史交易.持倉資料(double) 持倉單號 型別

取得歷史交易資料,資料型別小數(double)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_double_by_position_ticket",
  "title": "(MT5)持倉號取歷史交易.持倉資料(double) 持倉單號 型別",
  "tooltip": "取得歷史交易資料,資料型別小數(double)",
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
      "name": "HISTORY_DOUBLE_INFO",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "成交量",
          "value": "0"
        },
        {
          "label": "左L反向手數",
          "value": "1"
        },
        {
          "label": "右R同向手數",
          "value": "2"
        },
        {
          "label": "下單/掛單價格",
          "value": "3"
        },
        {
          "label": "手續費",
          "value": "4"
        },
        {
          "label": "隔夜利息",
          "value": "5"
        },
        {
          "label": "盈利",
          "value": "6"
        },
        {
          "label": "費用",
          "value": "7"
        },
        {
          "label": "下單/掛單SL價格",
          "value": "8"
        },
        {
          "label": "出場止損價格",
          "value": "9"
        },
        {
          "label": "下單/掛單TP價格",
          "value": "10"
        },
        {
          "label": "出場停利價格",
          "value": "11"
        },
        {
          "label": "平倉/掛單/CloseBy市價",
          "value": "12"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_double_by_position_ticket\"><field name=\"HISTORY_DOUBLE_INFO\">0</field></block>"
}
```
