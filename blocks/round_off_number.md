# round_off_number

取得該數值小數點後位數 數值 第幾位

取得最小報價點

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "round_off_number",
  "title": "取得該數值小數點後位數 數值 第幾位",
  "tooltip": "取得最小報價點",
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
      "name": "DOUBLE_NUMBER",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DECIMAL_DIGITS",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"round_off_number\"></block>"
}
```
