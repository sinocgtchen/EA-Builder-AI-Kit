# object_ChartXYToTimePrice

圖表座標轉成時間價格 X座標 Y座標 角落 時間/價格

利用圖表上的x及y座標(左上角為(0,0)座標)轉成時間及價格

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_ChartXYToTimePrice",
  "title": "圖表座標轉成時間價格 X座標 Y座標 角落 時間/價格",
  "tooltip": "利用圖表上的x及y座標(左上角為(0,0)座標)轉成時間及價格",
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
      "name": "POSITION_X",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "POSITION_Y",
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
      "name": "CHART_TIME_PRICE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "時間",
          "value": "0"
        },
        {
          "label": "價格",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_ChartXYToTimePrice\"><field name=\"CORNER\">CORNER_LEFT_UPPER</field><field name=\"CHART_TIME_PRICE\">0</field></block>"
}
```
