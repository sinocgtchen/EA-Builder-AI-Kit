# lists_getSublist

陣列 取得子陣列 到

複製陣列中指定的部分。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_getSublist",
  "title": "陣列 取得子陣列 到",
  "tooltip": "複製陣列中指定的部分。",
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
      "name": "LIST",
      "kind": "value",
      "connectionChecks": [
        "Array"
      ]
    },
    {
      "name": "AT1",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "AT2",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "WHERE1",
      "value": "FROM_START",
      "kind": "dropdown",
      "options": [
        {
          "label": "從 #",
          "value": "FROM_START"
        },
        {
          "label": "從倒數 #",
          "value": "FROM_END"
        },
        {
          "label": "從 頭",
          "value": "FIRST"
        }
      ]
    },
    {
      "name": "WHERE2",
      "value": "FROM_START",
      "kind": "dropdown",
      "options": [
        {
          "label": "#",
          "value": "FROM_START"
        },
        {
          "label": "倒數 # 位",
          "value": "FROM_END"
        },
        {
          "label": "最後",
          "value": "LAST"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_getSublist\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" at1=\"true\" at2=\"true\"></mutation><field name=\"WHERE1\">FROM_START</field><field name=\"WHERE2\">FROM_START</field></block>"
}
```
