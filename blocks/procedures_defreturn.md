# procedures_defreturn

到 回傳

創建一個有回傳值的函數。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "procedures_defreturn",
  "title": "到 回傳",
  "tooltip": "創建一個有回傳值的函數。",
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
    },
    {
      "name": "RETURN",
      "kind": "value",
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
    },
    {
      "name": "TYPE",
      "value": "bool",
      "kind": "dropdown",
      "options": [
        {
          "label": "bool",
          "value": "bool"
        },
        {
          "label": "ulong",
          "value": "ulong"
        },
        {
          "label": "long",
          "value": "long"
        },
        {
          "label": "double",
          "value": "double"
        },
        {
          "label": "uint",
          "value": "uint"
        },
        {
          "label": "int",
          "value": "int"
        },
        {
          "label": "string",
          "value": "string"
        },
        {
          "label": "datetime",
          "value": "datetime"
        },
        {
          "label": "color",
          "value": "color"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"procedures_defreturn\"><field name=\"NAME\"></field><field name=\"TYPE\">bool</field></block>"
}
```
