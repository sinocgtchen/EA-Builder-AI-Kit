# procedures_defnoreturn

到

創建一個無回傳值的函數。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "procedures_defnoreturn",
  "title": "到",
  "tooltip": "創建一個無回傳值的函數。",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "STACK",
      "kind": "statement",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "NAME",
      "value": "",
      "kind": "field",
      "options": null
    },
    {
      "name": "PARAMS",
      "value": "",
      "kind": "field",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"procedures_defnoreturn\"><field name=\"NAME\"></field></block>"
}
```
