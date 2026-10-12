# check_SL_TP_for_trade

是否 停損停利符合下單最小距離 商品 停損價格 停利價格 下單方式

下單前檢查是否停損停利價格符合下單最小距離.

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_SL_TP_for_trade",
  "title": "是否 停損停利符合下單最小距離 商品 停損價格 停利價格 下單方式",
  "tooltip": "下單前檢查是否停損停利價格符合下單最小距離.",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "CURRENCY_PAIR",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "STOPLOSS_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "TAKEPROFIT_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "ORDER_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "多單",
          "value": "0"
        },
        {
          "label": "空單",
          "value": "1"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_SL_TP_for_trade\"><field name=\"ORDER_TYPE\">0</field></block>"
}
```
