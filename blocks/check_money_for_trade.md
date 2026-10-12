# check_money_for_trade

是否 保證金足夠交易 商品 手數 下單方式

檢查資金是否足夠交易

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_money_for_trade",
  "title": "是否 保證金足夠交易 商品 手數 下單方式",
  "tooltip": "檢查資金是否足夠交易",
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
      "name": "LOT",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_money_for_trade\"><field name=\"ORDER_TYPE\">0</field></block>"
}
```
