# lists_split

用分隔符

將文本變成清單項目，按分隔符號拆分。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_split",
  "title": "用分隔符",
  "tooltip": "將文本變成清單項目，按分隔符號拆分。",
  "offeredInToolbox": {
    "ea": false,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": true,
    "mt5script": true
  },
  "inputs": [
    {
      "name": "INPUT",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "DELIM",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    }
  ],
  "fields": [
    {
      "name": "MODE",
      "value": "SPLIT",
      "kind": "dropdown",
      "options": [
        {
          "label": "從文本製作清單",
          "value": "SPLIT"
        },
        {
          "label": "從清單拆出文本",
          "value": "JOIN"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Array"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_split\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" mode=\"SPLIT\"></mutation><field name=\"MODE\">SPLIT</field></block>"
}
```
