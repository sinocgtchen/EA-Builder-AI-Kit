# get_ima_methods



MA方式

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_ima_methods",
  "title": "",
  "tooltip": "MA方式",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "IMA_METHODS",
      "value": "MODE_SMA",
      "kind": "dropdown",
      "options": [
        {
          "label": "簡單平均數",
          "value": "MODE_SMA"
        },
        {
          "label": "指數平均數",
          "value": "MODE_EMA"
        },
        {
          "label": "平滑平均數",
          "value": "MODE_SMMA"
        },
        {
          "label": "線性平均數",
          "value": "MODE_LWMA"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_ima_methods\"><field name=\"IMA_METHODS\">MODE_SMA</field></block>"
}
```
