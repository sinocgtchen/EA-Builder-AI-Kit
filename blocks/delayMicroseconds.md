# delayMicroseconds

延遲微秒

延遲指定時間(1000微秒=1毫秒)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "delayMicroseconds",
  "title": "延遲微秒",
  "tooltip": "延遲指定時間(1000微秒=1毫秒)",
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
    }
  ],
  "fields": [
    {
      "name": "DELAY_TIME",
      "value": "1000",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"delayMicroseconds\"><field name=\"DELAY_TIME\">1000</field></block>"
}
```
