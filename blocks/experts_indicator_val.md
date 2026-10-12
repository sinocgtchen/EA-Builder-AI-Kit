# experts_indicator_val

指標

返回指標參數

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "experts_indicator_val",
  "title": "指標",
  "tooltip": "返回指標參數",
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
    }
  ],
  "fields": [
    {
      "name": "name_",
      "value": "",
      "kind": "variable",
      "options": null
    },
    {
      "name": "val_",
      "value": "MACD",
      "kind": "dropdown",
      "options": [
        {
          "label": "MACD",
          "value": "MACD"
        },
        {
          "label": "RSI",
          "value": "RSI"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"experts_indicator_val\"><field name=\"name_\" id=\"var-29d62f44c5cd\">indicator</field><field name=\"val_\">MACD</field></block>"
}
```
