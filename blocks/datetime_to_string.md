# datetime_to_string

指定時間表示成文字字串 年 月 日 時 分

../../block-help/8-12.htm

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "datetime_to_string",
  "title": "指定時間表示成文字字串 年 月 日 時 分",
  "tooltip": "../../block-help/8-12.htm",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"datetime_to_string\"></block>"
}
```
