# mql_onchartevent

回測模式 圖形驅動事件(onChartEvent)

圖表事件處理

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "mql_onchartevent",
  "title": "回測模式 圖形驅動事件(onChartEvent)",
  "tooltip": "圖表事件處理",
  "offeredInToolbox": {
    "ea": true,
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
    },
    {
      "name": "OnChartEvent",
      "kind": "statement",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "m1",
      "value": "FALSE",
      "kind": "field",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"mql_onchartevent\"><field name=\"m1\">FALSE</field></block>"
}
```
