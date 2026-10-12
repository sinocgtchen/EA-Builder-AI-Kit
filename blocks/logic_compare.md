# logic_compare



如果這兩個輸入區塊內容相等，返回 真。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "logic_compare",
  "title": "",
  "tooltip": "如果這兩個輸入區塊內容相等，返回 真。",
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
      "connectionChecks": null
    },
    {
      "name": "B",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "OP",
      "value": "EQ",
      "kind": "dropdown",
      "options": [
        {
          "label": "=",
          "value": "EQ"
        },
        {
          "label": "≠",
          "value": "NEQ"
        },
        {
          "label": "‏<",
          "value": "LT"
        },
        {
          "label": "‏≤",
          "value": "LTE"
        },
        {
          "label": "‏>",
          "value": "GT"
        },
        {
          "label": "‏≥",
          "value": "GTE"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"logic_compare\"><field name=\"OP\">EQ</field></block>"
}
```
