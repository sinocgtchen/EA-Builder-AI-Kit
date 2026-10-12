# lists_create_with

使用這些值建立陣列

建立一個具備任意數量項目的陣列。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_create_with",
  "title": "使用這些值建立陣列",
  "tooltip": "建立一個具備任意數量項目的陣列。",
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
      "name": "ADD0",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "ADD1",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "ADD2",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Array"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_create_with\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" items=\"3\"></mutation></block>"
}
```
