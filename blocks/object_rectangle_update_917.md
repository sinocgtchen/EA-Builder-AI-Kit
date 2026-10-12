# object_rectangle_update_917

更新矩形方塊 編號 寬度 高度 顏色

更新矩形方塊

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_rectangle_update_917",
  "title": "更新矩形方塊 編號 寬度 高度 顏色",
  "tooltip": "更新矩形方塊",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "OBJECT_ID",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "RECT_WIDTH",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "RECT_HEIGHT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "LINE_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_rectangle_update_917\"></block>"
}
```
