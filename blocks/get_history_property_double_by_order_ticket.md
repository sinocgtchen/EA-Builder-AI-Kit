# get_history_property_double_by_order_ticket

(MT5)訂單號取歷史交易.訂單資料(double) 訂單單號 型別

取得歷史交易資料,資料型別小數(double)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_double_by_order_ticket",
  "title": "(MT5)訂單號取歷史交易.訂單資料(double) 訂單單號 型別",
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
      "value": "ORDER_VOLUME_INITIAL",
      "kind": "dropdown",
      "options": [
        {
          "label": "初始交易量",
          "value": "ORDER_VOLUME_INITIAL"
        },
        {
          "label": "當前交易量",
          "value": "ORDER_VOLUME_CURRENT"
        },
        {
          "label": "指定下單價格",
          "value": "ORDER_PRICE_OPEN"
        },
        {
          "label": "停損價格",
          "value": "ORDER_SL"
        },
        {
          "label": "停利價格",
          "value": "ORDER_TP"
        },
        {
          "label": "當前價格",
          "value": "ORDER_PRICE_CURRENT"
        },
        {
          "label": "StopLimit價格",
          "value": "ORDER_PRICE_STOPLIMIT"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_double_by_order_ticket\"><field name=\"HISTORY_DOUBLE_INFO\">ORDER_VOLUME_INITIAL</field></block>"
}
```
