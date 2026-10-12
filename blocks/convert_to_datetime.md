# convert_to_datetime

指定時間 年 月 日 時 分

傳回給予指定時間的年月日時分秒 (datetime)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "convert_to_datetime",
  "title": "指定時間 年 月 日 時 分",
  "tooltip": "傳回給予指定時間的年月日時分秒 (datetime)",
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
    },
    {
      "name": "DATETIME_YEAR",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DATETIME_MONTH",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DATETIME_DAY",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DATETIME_HOUR",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DATETIME_MINU",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"convert_to_datetime\"></block>"
}
```
