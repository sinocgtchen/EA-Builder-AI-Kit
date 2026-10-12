# object_ChartTimePriceToXY

時間價格轉成圖表座標 時間 價格 角落 座標

利用時間及價格轉成圖表上的x及y座標(左上角為(0,0)座標)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_ChartTimePriceToXY",
  "title": "時間價格轉成圖表座標 時間 價格 角落 座標",
  "tooltip": "利用時間及價格轉成圖表上的x及y座標(左上角為(0,0)座標)",
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
      "name": "DATETIME_TIME",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "PRICE",
      "kind": "value",
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
    }
  ],
  "fields": [
    {
      "name": "CORNER",
      "value": "CORNER_LEFT_UPPER",
      "kind": "dropdown",
      "options": [
        {
          "label": "座標在左上角",
          "value": "CORNER_LEFT_UPPER"
        },
        {
          "label": "座標在左下角",
          "value": "CORNER_LEFT_LOWER"
        },
        {
          "label": "座標在右下角",
          "value": "CORNER_RIGHT_LOWER"
        },
        {
          "label": "座標在右上角",
          "value": "CORNER_RIGHT_UPPER"
        }
      ]
    },
    {
      "name": "XY_COORDINATES",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "x",
          "value": "0"
        },
        {
          "label": "y",
          "value": "1"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_ChartTimePriceToXY\"><field name=\"CORNER\">CORNER_LEFT_UPPER</field><field name=\"XY_COORDINATES\">0</field></block>"
}
```
