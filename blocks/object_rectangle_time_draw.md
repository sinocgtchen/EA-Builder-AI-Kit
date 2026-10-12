# object_rectangle_time_draw

利用時間價格建立矩形方塊 名稱 時間 價格 時間 價格 顏色 填滿

利用兩個時間及價格建立矩形方塊

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_rectangle_time_draw",
  "title": "利用時間價格建立矩形方塊 名稱 時間 價格 時間 價格 顏色 填滿",
  "tooltip": "利用兩個時間及價格建立矩形方塊",
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
      "name": "RECT_NAME",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "RECT_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
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
    }
  ],
  "fields": [
    {
      "name": "COLOR_FILL",
      "value": "TRUE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_rectangle_time_draw\"><field name=\"COLOR_FILL\">TRUE</field></block>"
}
```
