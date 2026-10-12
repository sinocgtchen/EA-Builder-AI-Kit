# object_triangle_draw

建立三角形物件 名稱 時間 價格 時間 價格 時間 價格 顏色

利用三個時間及價格建立三角形物件

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_triangle_draw",
  "title": "建立三角形物件 名稱 時間 價格 時間 價格 時間 價格 顏色",
  "tooltip": "利用三個時間及價格建立三角形物件",
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
      "name": "TRIANGLE_NAME",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "DATETIME_TIME1",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "PRICE1_Y",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "DATETIME_TIME2",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "PRICE2_Y",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "DATETIME_TIME3",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "PRICE3_Y",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "TRIANGLE_COLOR",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_triangle_draw\"></block>"
}
```
