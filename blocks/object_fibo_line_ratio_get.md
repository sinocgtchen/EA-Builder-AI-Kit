# object_fibo_line_ratio_get

取得FIBO曲線數值 名稱 切割率

取得FIBO曲線數值

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_fibo_line_ratio_get",
  "title": "取得FIBO曲線數值 名稱 切割率",
  "tooltip": "取得FIBO曲線數值",
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
      "name": "LINE_NAME",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "FIBO_RATIO",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_fibo_line_ratio_get\"></block>"
}
```
