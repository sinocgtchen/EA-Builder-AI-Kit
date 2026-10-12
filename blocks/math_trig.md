# math_trig



返回指定角度的正弦值(非弧度）。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "math_trig",
  "title": "",
  "tooltip": "返回指定角度的正弦值(非弧度）。",
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
      "name": "NUM",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "OP",
      "value": "SIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "sin",
          "value": "SIN"
        },
        {
          "label": "cos",
          "value": "COS"
        },
        {
          "label": "tan",
          "value": "TAN"
        },
        {
          "label": "asin",
          "value": "ASIN"
        },
        {
          "label": "acos",
          "value": "ACOS"
        },
        {
          "label": "atan",
          "value": "ATAN"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"math_trig\"><field name=\"OP\">SIN</field></block>"
}
```
