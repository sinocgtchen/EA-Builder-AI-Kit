# object_fibo_line_get

取得FIBO曲線數值 名稱 切割率

取得FIBO曲線數值

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_fibo_line_get",
  "title": "取得FIBO曲線數值 名稱 切割率",
  "tooltip": "取得FIBO曲線數值",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "LINE_NAME",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "FIBO_RATIO",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
        {
          "label": "23.6",
          "value": "23.6"
        },
        {
          "label": "38.2",
          "value": "38.2"
        },
        {
          "label": "50",
          "value": "50"
        },
        {
          "label": "61.8",
          "value": "61.8"
        },
        {
          "label": "70.0",
          "value": "70.0"
        },
        {
          "label": "100",
          "value": "100"
        },
        {
          "label": "161.8",
          "value": "161.8"
        },
        {
          "label": "261.8",
          "value": "261.8"
        },
        {
          "label": "423.6",
          "value": "423.6"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_fibo_line_get\"><field name=\"FIBO_RATIO\">0</field></block>"
}
```
