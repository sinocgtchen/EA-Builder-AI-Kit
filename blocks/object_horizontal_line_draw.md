# object_horizontal_line_draw

畫一條水平線 水平線名稱 價格 寬度 樣式 可移動 顏色

依價格在圖表中畫一條水平線

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_horizontal_line_draw",
  "title": "畫一條水平線 水平線名稱 價格 寬度 樣式 可移動 顏色",
  "tooltip": "依價格在圖表中畫一條水平線",
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
    },
    {
      "name": "PRICE_Y",
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
    },
    {
      "name": "LINE_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "LINE_WIDTH",
      "value": "1",
      "kind": "dropdown",
      "options": [
        {
          "label": "1",
          "value": "1"
        },
        {
          "label": "2",
          "value": "2"
        },
        {
          "label": "3",
          "value": "3"
        },
        {
          "label": "4",
          "value": "4"
        },
        {
          "label": "5",
          "value": "5"
        }
      ]
    },
    {
      "name": "LINE_STYLE",
      "value": "STYLE_SOLID",
      "kind": "dropdown",
      "options": [
        {
          "label": "實線",
          "value": "STYLE_SOLID"
        },
        {
          "label": "虛線",
          "value": "STYLE_DASH"
        },
        {
          "label": "點線",
          "value": "STYLE_DOT"
        },
        {
          "label": "1點1虛線",
          "value": "STYLE_DASHDOT"
        },
        {
          "label": "2點1虛線",
          "value": "STYLE_DASHDOTDOT"
        }
      ]
    },
    {
      "name": "MOVABLE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_horizontal_line_draw\"><field name=\"LINE_WIDTH\">1</field><field name=\"LINE_STYLE\">STYLE_SOLID</field><field name=\"MOVABLE\">TRUE</field></block>"
}
```
