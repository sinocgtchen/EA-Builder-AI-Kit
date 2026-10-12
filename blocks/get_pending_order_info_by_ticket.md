# get_pending_order_info_by_ticket

取得商品掛單資料(double) 單號 型別

取得商品掛單資料(Buy Limit/Sell Limit/Buy Stop/ Sell Stop/Buy Stop Limit/Sell Stop Limit)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_pending_order_info_by_ticket",
  "title": "取得商品掛單資料(double) 單號 型別",
  "tooltip": "取得商品掛單資料(Buy Limit/Sell Limit/Buy Stop/ Sell Stop/Buy Stop Limit/Sell Stop Limit)",
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
      "name": "PENDING_ORDER_DATA",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "訂單手數",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_pending_order_info_by_ticket\"><field name=\"PENDING_ORDER_DATA\">0</field></block>"
}
```
