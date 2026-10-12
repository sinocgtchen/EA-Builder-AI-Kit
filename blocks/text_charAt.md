# text_charAt

的字元在字串

返回位於指定位置的字元。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_charAt",
  "title": "的字元在字串",
  "tooltip": "返回位於指定位置的字元。",
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
      "name": "VALUE",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "AT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "WHERE",
      "value": "FROM_START",
      "kind": "dropdown",
      "options": [
        {
          "label": "取得 字元 #",
          "value": "FROM_START"
        },
        {
          "label": "取第一個字元",
          "value": "FIRST"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_charAt\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" at=\"true\"></mutation><field name=\"WHERE\">FROM_START</field></block>"
}
```
