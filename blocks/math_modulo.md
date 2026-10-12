# math_modulo

取餘數自 ÷

回傳兩個數字相除的餘數

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "math_modulo",
  "title": "取餘數自 ÷",
  "tooltip": "回傳兩個數字相除的餘數",
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
      "name": "DIVIDEND",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DIVISOR",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"math_modulo\"></block>"
}
```
