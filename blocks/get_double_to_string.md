# get_double_to_string

轉換型別 小數(double) 到 字串(string) 小數點後的位數

轉換型別 小數(double)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_double_to_string",
  "title": "轉換型別 小數(double) 到 字串(string) 小數點後的位數",
  "tooltip": "轉換型別 小數(double)",
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
      "name": "DOUBLE_DATA",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "DIGITS",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_double_to_string\"></block>"
}
```
