# check_weektime_session

是否 目前時間 在此時段 星期一 星期二 星期三 星期四 星期五 星期六 星期日 開始時間 點 分鐘 到 點 分鐘

檢查目前時間是否在每星期區間

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_weektime_session",
  "title": "是否 目前時間 在此時段 星期一 星期二 星期三 星期四 星期五 星期六 星期日 開始時間 點 分鐘 到 點 分鐘",
  "tooltip": "檢查目前時間是否在每星期區間",
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
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "START_HOUR",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "START_MINUTE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "END_HOUR",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "END_MINUTE",
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
  "fields": [
    {
      "name": "LOCAL_TIME",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "伺服器",
          "value": "0"
        },
        {
          "label": "客戶端",
          "value": "1"
        }
      ]
    },
    {
      "name": "m1",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m2",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m3",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m4",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m5",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m6",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m7",
      "value": "FALSE",
      "kind": "field",
      "options": null
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_weektime_session\"><field name=\"LOCAL_TIME\">0</field><field name=\"m1\">FALSE</field><field name=\"m2\">FALSE</field><field name=\"m3\">FALSE</field><field name=\"m4\">FALSE</field><field name=\"m5\">FALSE</field><field name=\"m6\">FALSE</field><field name=\"m7\">FALSE</field></block>"
}
```
