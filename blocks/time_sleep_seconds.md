# time_sleep_seconds

暫時停止一段時間 單位

EA暫時停止一段時間

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "time_sleep_seconds",
  "title": "暫時停止一段時間 單位",
  "tooltip": "EA暫時停止一段時間",
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
      "name": "TIME_SLOTS",
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
      "name": "TIME_UNIT",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "秒",
          "value": "0"
        },
        {
          "label": "分",
          "value": "1"
        },
        {
          "label": "時",
          "value": "2"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"time_sleep_seconds\"><field name=\"TIME_UNIT\">0</field></block>"
}
```
