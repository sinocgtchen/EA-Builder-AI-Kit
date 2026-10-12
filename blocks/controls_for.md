# controls_for

使用 從範圍 到 每隔 執行

從起始數到結尾數中取出變數 "i" 的值，按指定的時間間隔，執行指定的積木。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "controls_for",
  "title": "使用 從範圍 到 每隔 執行",
  "tooltip": "從起始數到結尾數中取出變數 \"i\" 的值，按指定的時間間隔，執行指定的積木。",
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
      "name": "FROM",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "TO",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "BY",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DO",
      "kind": "statement",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "VAR",
      "value": "",
      "kind": "variable",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"controls_for\"><field name=\"VAR\" id=\"var-de7d1b721a1e\">i</field></block>"
}
```
