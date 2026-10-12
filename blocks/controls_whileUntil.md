# controls_whileUntil

重複 執行

當值為真時，執行一些語句

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "controls_whileUntil",
  "title": "重複 執行",
  "tooltip": "當值為真時，執行一些語句",
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
      "name": "BOOL",
      "kind": "value",
      "connectionChecks": [
        "Boolean"
      ]
    },
    {
      "name": "DO",
      "kind": "statement",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "MODE",
      "value": "WHILE",
      "kind": "dropdown",
      "options": [
        {
          "label": "當",
          "value": "WHILE"
        },
        {
          "label": "直到",
          "value": "UNTIL"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"controls_whileUntil\"><field name=\"MODE\">WHILE</field></block>"
}
```
