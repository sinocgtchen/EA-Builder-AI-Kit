# get_history_property_datetime_by_position_ticket

(MT5)持倉號取歷史交易.持倉資料(long/int) 持倉單號 型別

取得歷史交易資料,資料型別日期時間(long/int)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_datetime_by_position_ticket",
  "title": "(MT5)持倉號取歷史交易.持倉資料(long/int) 持倉單號 型別",
  "tooltip": "取得歷史交易資料,資料型別日期時間(long/int)",
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
      "name": "HISTORY_DATETIME_INFO",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "魔術數字",
          "value": "0"
        },
        {
          "label": "下單/掛單時間",
          "value": "1"
        },
        {
          "label": "平倉/取消時間",
          "value": "2"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_datetime_by_position_ticket\"><field name=\"HISTORY_DATETIME_INFO\">0</field></block>"
}
```
