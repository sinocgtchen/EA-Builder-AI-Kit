# object_fibo_ratio



取得FIBO曲線數值

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_fibo_ratio",
  "title": "",
  "tooltip": "取得FIBO曲線數值",
  "offeredInToolbox": {
    "ea": true,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": false,
    "mt5script": false
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
      "name": "FIBO_RATIO_LIST",
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
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_fibo_ratio\"><field name=\"FIBO_RATIO_LIST\">0</field></block>"
}
```
