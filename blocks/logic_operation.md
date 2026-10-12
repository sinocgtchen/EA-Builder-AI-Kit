# logic_operation



如果這兩個輸入值都為 真，則返回 真。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "logic_operation",
  "title": "",
  "tooltip": "如果這兩個輸入值都為 真，則返回 真。",
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
      "name": "A",
      "kind": "value",
      "connectionChecks": [
        "Boolean"
      ]
    },
    {
      "name": "B",
      "kind": "value",
      "connectionChecks": [
        "Boolean"
      ]
    }
  ],
  "fields": [
    {
      "name": "OP",
      "value": "AND",
      "kind": "dropdown",
      "options": [
        {
          "label": "且",
          "value": "AND"
        },
        {
          "label": "或",
          "value": "OR"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"logic_operation\"><field name=\"OP\">AND</field></block>"
}
```
