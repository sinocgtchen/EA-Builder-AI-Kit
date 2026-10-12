# get_string_to

轉換型別 字串 到 型別

轉換型別 字串到整數或浮點數

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_string_to",
  "title": "轉換型別 字串 到 型別",
  "tooltip": "轉換型別 字串到整數或浮點數",
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
      "name": "STRING_DATA",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TYPE_INFO",
      "value": "Double",
      "kind": "dropdown",
      "options": [
        {
          "label": "小數(double)",
          "value": "Double"
        },
        {
          "label": "整數(int)",
          "value": "Integer"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_string_to\"><field name=\"TYPE_INFO\">Double</field></block>"
}
```
