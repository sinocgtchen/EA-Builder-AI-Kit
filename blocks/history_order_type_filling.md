# history_order_type_filling

(MT5)歷史訂單成交量執行方式

歷史訂單成交量執行方式

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_order_type_filling",
  "title": "(MT5)歷史訂單成交量執行方式",
  "tooltip": "歷史訂單成交量執行方式",
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
      "name": "ORDER_FILLING",
      "value": "ORDER_FILLING_FOK",
      "kind": "dropdown",
      "options": [
        {
          "label": "全部成交否則取消",
          "value": "ORDER_FILLING_FOK"
        },
        {
          "label": "立即成交否則取消",
          "value": "ORDER_FILLING_IOC"
        },
        {
          "label": "全部成交或等待",
          "value": "ORDER_FILLING_BOC"
        },
        {
          "label": "立即成交剩餘部分為掛單",
          "value": "ORDER_FILLING_RETURN"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_order_type_filling\"><field name=\"ORDER_FILLING\">ORDER_FILLING_FOK</field></block>"
}
```
