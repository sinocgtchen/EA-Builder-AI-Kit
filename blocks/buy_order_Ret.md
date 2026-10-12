# buy_order_Ret

多單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色

多單下單(回傳單號 ticket)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "buy_order_Ret",
  "title": "多單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色",
  "tooltip": "多單下單(回傳單號 ticket)",
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
      "name": "LOT",
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
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "SL_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "SL_PRICE",
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
      "name": "TP_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "TP_PRICE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"buy_order_Ret\"><field name=\"SL_CHECKED\">TRUE</field><field name=\"SL_PRICE\">0</field><field name=\"TP_CHECKED\">TRUE</field><field name=\"TP_PRICE\">0</field></block>"
}
```
