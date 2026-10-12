# math_single



返回指定數字的平方根。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "math_single",
  "title": "",
  "tooltip": "返回指定數字的平方根。",
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
      "value": "ROOT",
      "kind": "dropdown",
      "options": [
        {
          "label": "開根號",
          "value": "ROOT"
        },
        {
          "label": "絕對值",
          "value": "ABS"
        },
        {
          "label": "四捨五入",
          "value": "ROUND"
        },
        {
          "label": "無條件進位",
          "value": "ROUNDUP"
        },
        {
          "label": "無條件捨去",
          "value": "ROUNDDOWN"
        },
        {
          "label": "-",
          "value": "NEG"
        },
        {
          "label": "ln",
          "value": "LN"
        },
        {
          "label": "log10",
          "value": "LOG10"
        },
        {
          "label": "e^",
          "value": "EXP"
        },
        {
          "label": "10^",
          "value": "POW10"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"math_single\"><field name=\"OP\">ROOT</field></block>"
}
```
