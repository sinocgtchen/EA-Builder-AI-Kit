# time_sleep

暫時停止一段時間

EA暫時停止一段時間

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "time_sleep",
  "title": "暫時停止一段時間",
  "tooltip": "EA暫時停止一段時間",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TIME_SLOTS",
      "value": "60000",
      "kind": "dropdown",
      "options": [
        {
          "label": "1分鐘",
          "value": "60000"
        },
        {
          "label": "10分鐘",
          "value": "600000"
        },
        {
          "label": "30分鐘",
          "value": "1800000"
        },
        {
          "label": "1小時",
          "value": "3600000"
        },
        {
          "label": "2小時",
          "value": "7200000"
        },
        {
          "label": "5小時",
          "value": "18000000"
        },
        {
          "label": "10小時",
          "value": "36000000"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"time_sleep\"><field name=\"TIME_SLOTS\">60000</field></block>"
}
```
