# object_horizontal_line_get

取得圖表中水平線價格 水平線名稱

取得圖表中水平線價格,通常用於手動畫線在圖表上

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_horizontal_line_get",
  "title": "取得圖表中水平線價格 水平線名稱",
  "tooltip": "取得圖表中水平線價格,通常用於手動畫線在圖表上",
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
      "name": "LINE_NAME",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_horizontal_line_get\"></block>"
}
```
