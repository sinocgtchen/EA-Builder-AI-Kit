# variables_declare

宣 告 當 資料

宣告變數及資料型態

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "variables_declare",
  "title": "宣 告 當 資料",
  "tooltip": "宣告變數及資料型態",
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
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TYPE_PARAMETERS",
      "value": "general",
      "kind": "dropdown",
      "options": [
        {
          "label": "一般參數",
          "value": "general"
        },
        {
          "label": "輸入參數(Input)",
          "value": "input"
        },
        {
          "label": "陣列",
          "value": "array"
        }
      ]
    },
    {
      "name": "VAR",
      "value": "",
      "kind": "variable",
      "options": null
    },
    {
      "name": "TYPE",
      "value": "double",
      "kind": "dropdown",
      "options": [
        {
          "label": "double",
          "value": "double"
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
          "label": "bool",
          "value": "bool"
        },
        {
          "label": "long",
          "value": "long"
        },
        {
          "label": "datetime",
          "value": "datetime"
        },
        {
          "label": "uint",
          "value": "uint"
        },
        {
          "label": "ulong",
          "value": "ulong"
        },
        {
          "label": "color",
          "value": "color"
        },
        {
          "label": "enum",
          "value": "enum"
        },
        {
          "label": "timeframes",
          "value": "ENUM_TIMEFRAMES"
        },
        {
          "label": "ima_method",
          "value": "ENUM_MA_METHOD"
        },
        {
          "label": "applied_price",
          "value": "ENUM_APPLIED_PRICE"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"variables_declare\"><field name=\"TYPE_PARAMETERS\">general</field><field name=\"VAR\" id=\"var-19b5ded2381d\">變數</field><field name=\"TYPE\">double</field></block>"
}
```
