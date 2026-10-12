# DynamicLot_Size

依風險百分比取得手數 偶數輸出 商品 風險依據 百分比 停損(點差)

百分比依風險計算手數

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "DynamicLot_Size",
  "title": "依風險百分比取得手數 偶數輸出 商品 風險依據 百分比 停損(點差)",
  "tooltip": "百分比依風險計算手數",
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
      "name": "PERCENTAGE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "STOP_LOSS_PIP",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "EVEN",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "TYPE_AMOUNT",
      "value": "EQUITY",
      "kind": "dropdown",
      "options": [
        {
          "label": "淨值",
          "value": "EQUITY"
        },
        {
          "label": "餘額",
          "value": "BALANCE"
        },
        {
          "label": "可用保證金",
          "value": "FREE_MARGIN"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"DynamicLot_Size\"><field name=\"EVEN\">FALSE</field><field name=\"TYPE_AMOUNT\">EQUITY</field></block>"
}
```
