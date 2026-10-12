# order_modify_by_open_market_price

修改停損停利 商品 魔術數字 下單方式 依照價格 停損 停利 顏色

依照市場價格或下單價格修改部位的停損價格及停利價格

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "order_modify_by_open_market_price",
  "title": "修改停損停利 商品 魔術數字 下單方式 依照價格 停損 停利 顏色",
  "tooltip": "依照市場價格或下單價格修改部位的停損價格及停利價格",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
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
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "SYMBOL_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "MAGIC_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "ORDER_TYPE",
      "value": "OP_BUY",
      "kind": "dropdown",
      "options": [
        {
          "label": "多單",
          "value": "OP_BUY"
        },
        {
          "label": "空單",
          "value": "OP_SELL"
        }
      ]
    },
    {
      "name": "PRICE_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "下單價格",
          "value": "0"
        },
        {
          "label": "市場價格",
          "value": "1"
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
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"order_modify_by_open_market_price\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"ORDER_TYPE\">OP_BUY</field><field name=\"PRICE_TYPE\">0</field><field name=\"SL_CHECKED\">TRUE</field><field name=\"SL_PRICE\">0</field><field name=\"TP_CHECKED\">TRUE</field><field name=\"TP_PRICE\">0</field></block>"
}
```
