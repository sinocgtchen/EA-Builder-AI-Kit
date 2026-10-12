# prices_to_points

價格1 減去 價格2 (返回點差) 商品 價格1 價格2

計算 價格1 減去 價格2 (返回點差)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "prices_to_points",
  "title": "價格1 減去 價格2 (返回點差) 商品 價格1 價格2",
  "tooltip": "計算 價格1 減去 價格2 (返回點差)",
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
      "name": "FIRST_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "SECOND_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"prices_to_points\"></block>"
}
```
