# math_arithmetic



返回兩個數字的總和。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "math_arithmetic",
  "title": "",
  "tooltip": "返回兩個數字的總和。",
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
        "Number"
      ]
    },
    {
      "name": "B",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "OP",
      "value": "ADD",
      "kind": "dropdown",
      "options": [
        {
          "label": "+",
          "value": "ADD"
        },
        {
          "label": "-",
          "value": "MINUS"
        },
        {
          "label": "×",
          "value": "MULTIPLY"
        },
        {
          "label": "÷",
          "value": "DIVIDE"
        },
        {
          "label": "^",
          "value": "POWER"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"math_arithmetic\"><field name=\"OP\">ADD</field></block>"
}
```
