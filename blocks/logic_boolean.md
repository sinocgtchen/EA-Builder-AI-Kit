# logic_boolean



返回 真 或 否。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "logic_boolean",
  "title": "",
  "tooltip": "返回 真 或 否。",
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
    }
  ],
  "fields": [
    {
      "name": "BOOL",
      "value": "TRUE",
      "kind": "dropdown",
      "options": [
        {
          "label": "真",
          "value": "TRUE"
        },
        {
          "label": "否",
          "value": "FALSE"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"logic_boolean\"><field name=\"BOOL\">TRUE</field></block>"
}
```
