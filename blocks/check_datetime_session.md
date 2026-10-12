# check_datetime_session

是否 目前時間 在此時段 開始日期 到

檢查日期是否在某時段

支援產生器：mt4, mt5, mt4script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_datetime_session",
  "title": "是否 目前時間 在此時段 開始日期 到",
  "tooltip": "檢查日期是否在某時段",
  "offeredInToolbox": {
    "ea": true,
    "script": true
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": true,
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
      "name": "START_DATE",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "END_DATE",
      "kind": "value",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_datetime_session\"><field name=\"LOCAL_TIME\">0</field></block>"
}
```
