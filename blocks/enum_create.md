# enum_create

建立列舉式資料(enum) 變數名稱

宣告一個列舉式資料型態

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "enum_create",
  "title": "建立列舉式資料(enum) 變數名稱",
  "tooltip": "宣告一個列舉式資料型態",
  "offeredInToolbox": {
    "ea": true,
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "ADD0",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "ADD1",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "ENUM_NAME",
      "value": "",
      "kind": "variable",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"enum_create\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" items=\"2\"></mutation><field name=\"ENUM_NAME\" id=\"var-e2dede6e1d03\">MagicNumber</field></block>"
}
```
