# get_history_property_datetime_by_order_ticket

(MT5)訂單號取歷史交易.訂單資料(long/int) 訂單單號 型別

取得歷史交易資料,資料型別日期時間(long/int)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_datetime_by_order_ticket",
  "title": "(MT5)訂單號取歷史交易.訂單資料(long/int) 訂單單號 型別",
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
      "value": "ORDER_TICKET",
      "kind": "dropdown",
      "options": [
        {
          "label": "單號",
          "value": "ORDER_TICKET"
        },
        {
          "label": "設置時間",
          "value": "ORDER_TIME_SETUP"
        },
        {
          "label": "掛單方式",
          "value": "ORDER_TYPE"
        },
        {
          "label": "訂單狀況",
          "value": "ORDER_STATE"
        },
        {
          "label": "期限終止時間",
          "value": "ORDER_TIME_EXPIRATION"
        },
        {
          "label": "執行或取消時間",
          "value": "ORDER_TIME_DONE"
        },
        {
          "label": "下單時間(long)",
          "value": "ORDER_TIME_SETUP_MSC"
        },
        {
          "label": "執行或取消時間(long)",
          "value": "ORDER_TIME_DONE_MSC"
        },
        {
          "label": "成交量執行方式",
          "value": "ORDER_TYPE_FILLING"
        },
        {
          "label": "有效期間",
          "value": "ORDER_TYPE_TIME"
        },
        {
          "label": "魔術數字",
          "value": "ORDER_MAGIC"
        },
        {
          "label": "訂單原因",
          "value": "ORDER_REASON"
        },
        {
          "label": "訂單進場單號",
          "value": "ORDER_POSITION_ID"
        },
        {
          "label": "反向對沖出場單號",
          "value": "ORDER_POSITION_BY_ID"
        },
        {
          "label": "對應的成交單號",
          "value": "1"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_datetime_by_order_ticket\"><field name=\"HISTORY_DATETIME_INFO\">ORDER_TICKET</field></block>"
}
```
