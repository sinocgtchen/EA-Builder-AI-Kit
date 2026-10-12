# pending_order_pip_price_noRet

掛單 商品 魔術數字 掛單方式 手數 價格 最大滑點 停損 停利 註解 有效期 顏色

掛單

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "pending_order_pip_price_noRet",
  "title": "掛單 商品 魔術數字 掛單方式 手數 價格 最大滑點 停損 停利 註解 有效期 顏色",
  "tooltip": "掛單",
  "offeredInToolbox": {
    "ea": false,
    "script": false
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
      "name": "MAGIC_NUMBER",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "LOT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "ORDER_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "SLIPPAGE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "STOP_LOSS",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "TAKE_PROFIT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "COMMENTS",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "TIME_SETTING",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "PIP_PRICE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "點差",
          "value": "0"
        },
        {
          "label": "價格",
          "value": "1"
        }
      ]
    },
    {
      "name": "ORDER_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "BuyLimit",
          "value": "0"
        },
        {
          "label": "SelLlimit",
          "value": "1"
        },
        {
          "label": "BuyStop",
          "value": "2"
        },
        {
          "label": "SellStop",
          "value": "3"
        },
        {
          "label": "BuyStopLimit",
          "value": "4"
        },
        {
          "label": "SellStopLimit",
          "value": "5"
        }
      ]
    },
    {
      "name": "SL_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "TP_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"pending_order_pip_price_noRet\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" stoplimit_input=\"false\"></mutation><field name=\"PIP_PRICE\">0</field><field name=\"ORDER_TYPE\">0</field><field name=\"SL_CHECKED\">TRUE</field><field name=\"TP_CHECKED\">TRUE</field></block>"
}
```
