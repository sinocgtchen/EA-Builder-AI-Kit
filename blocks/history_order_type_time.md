# history_order_type_time

(MT5)歷史訂單有效期間

歷史訂單有效時間

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_order_type_time",
  "title": "(MT5)歷史訂單有效期間",
  "tooltip": "歷史訂單有效時間",
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
    }
  ],
  "fields": [
    {
      "name": "ORDER_TIME",
      "value": "ORDER_TIME_GTC",
      "kind": "dropdown",
      "options": [
        {
          "label": "直到刪除",
          "value": "ORDER_TIME_GTC"
        },
        {
          "label": "直到交易日結束",
          "value": "ORDER_TIME_DAY"
        },
        {
          "label": "直到訂單過期",
          "value": "ORDER_TIME_SPECIFIED"
        },
        {
          "label": "直到指定時間",
          "value": "ORDER_TIME_SPECIFIED_DAY"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_order_type_time\"><field name=\"ORDER_TIME\">ORDER_TIME_GTC</field></block>"
}
```
