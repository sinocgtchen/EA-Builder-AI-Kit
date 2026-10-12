# get_history_property_datetime_by_deal_ticket

(MT5)成交號取歷史交易.成交資料(long/int) 成交單號 型別

取得歷史交易資料,資料型別日期時間(long/int)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_datetime_by_deal_ticket",
  "title": "(MT5)成交號取歷史交易.成交資料(long/int) 成交單號 型別",
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
      "value": "DEAL_TICKET",
      "kind": "dropdown",
      "options": [
        {
          "label": "成交單號",
          "value": "DEAL_TICKET"
        },
        {
          "label": "成交的訂單號",
          "value": "DEAL_ORDER"
        },
        {
          "label": "交易時間",
          "value": "DEAL_TIME"
        },
        {
          "label": "交易時間(毫秒)",
          "value": "DEAL_TIME_MSC"
        },
        {
          "label": "交易方式",
          "value": "DEAL_TYPE"
        },
        {
          "label": "成交進出類型",
          "value": "DEAL_ENTRY"
        },
        {
          "label": "魔術數字",
          "value": "DEAL_MAGIC"
        },
        {
          "label": "成交原因",
          "value": "DEAL_REASON"
        },
        {
          "label": "下單時訂單號",
          "value": "DEAL_POSITION_ID"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_datetime_by_deal_ticket\"><field name=\"HISTORY_DATETIME_INFO\">DEAL_TICKET</field></block>"
}
```
