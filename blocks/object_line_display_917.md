# object_line_display_917

畫區隔線 編號 區隔線字元 角落 水平位置 垂直位置 寬度 顏色

畫區隔線到圖表

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_line_display_917",
  "title": "畫區隔線 編號 區隔線字元 角落 水平位置 垂直位置 寬度 顏色",
  "tooltip": "畫區隔線到圖表",
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
      "name": "X_DISTANCE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "Y_DISTANCE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "LINE_WIDTH",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "CHAR_LINE",
      "value": "=",
      "kind": "dropdown",
      "options": [
        {
          "label": "=",
          "value": "="
        },
        {
          "label": "-",
          "value": "-"
        },
        {
          "label": "*",
          "value": "*"
        },
        {
          "label": "#",
          "value": "#"
        },
        {
          "label": "$",
          "value": "$"
        },
        {
          "label": "●",
          "value": "●"
        },
        {
          "label": "👓",
          "value": "👓"
        }
      ]
    },
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
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_line_display_917\"><field name=\"CHAR_LINE\">=</field><field name=\"CORNER\">CORNER_LEFT_UPPER</field></block>"
}
```
