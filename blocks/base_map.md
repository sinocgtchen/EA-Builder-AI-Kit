# base_map

對應  數值 到 [ - ]

重新對應數值[0-1023]到另一個範圍.

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "base_map",
  "title": "對應  數值 到 [ - ]",
  "tooltip": "重新對應數值[0-1023]到另一個範圍.",
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
      "name": "NUM",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DMIN",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DMAX",
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
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"base_map\"></block>"
}
```
