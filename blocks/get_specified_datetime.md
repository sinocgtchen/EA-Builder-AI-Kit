# get_specified_datetime

取得 指定時間 時間

傳回指定時間的區間數值,整數int

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_specified_datetime",
  "title": "取得 指定時間 時間",
  "tooltip": "傳回指定時間的區間數值,整數int",
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
      "name": "SPECIFIED_DATETIME",
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
      "name": "DATETIME",
      "value": "TimeYear",
      "kind": "dropdown",
      "options": [
        {
          "label": "年",
          "value": "TimeYear"
        },
        {
          "label": "月",
          "value": "TimeMonth"
        },
        {
          "label": "時",
          "value": "TimeHour"
        },
        {
          "label": "分",
          "value": "TimeMinute"
        },
        {
          "label": "秒",
          "value": "TimeSeconds"
        },
        {
          "label": "星期(1,2,3,4,5,6,0)",
          "value": "TimeDayOfWeek"
        },
        {
          "label": "月中日期(1~31)",
          "value": "TimeDay"
        },
        {
          "label": "年中日期(1~365)",
          "value": "TimeDayOfYear"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_specified_datetime\"><field name=\"DATETIME\">TimeYear</field></block>"
}
```
