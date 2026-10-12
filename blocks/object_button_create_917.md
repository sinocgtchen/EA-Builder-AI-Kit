# object_button_create_917

建立按鈕 編號 名稱 角落 水平位置 垂直位置 寬度 字體大小 文字顏色 背景顏色

建立一個按鈕在圖表上

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_button_create_917",
  "title": "建立按鈕 編號 名稱 角落 水平位置 垂直位置 寬度 字體大小 文字顏色 背景顏色",
  "tooltip": "建立一個按鈕在圖表上",
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
      "name": "BUTTON_TEXT",
      "kind": "value",
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
      "name": "TEXT_WIDTH",
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
      "name": "TEXT_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    },
    {
      "name": "BG_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
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
      "name": "FONT_SIZE",
      "value": "7",
      "kind": "dropdown",
      "options": [
        {
          "label": "7",
          "value": "7"
        },
        {
          "label": "8",
          "value": "8"
        },
        {
          "label": "9",
          "value": "9"
        },
        {
          "label": "10",
          "value": "10"
        },
        {
          "label": "11",
          "value": "11"
        },
        {
          "label": "12",
          "value": "12"
        },
        {
          "label": "13",
          "value": "13"
        },
        {
          "label": "14",
          "value": "14"
        },
        {
          "label": "15",
          "value": "15"
        },
        {
          "label": "16",
          "value": "16"
        },
        {
          "label": "17",
          "value": "17"
        },
        {
          "label": "18",
          "value": "18"
        },
        {
          "label": "19",
          "value": "19"
        },
        {
          "label": "20",
          "value": "20"
        },
        {
          "label": "21",
          "value": "21"
        },
        {
          "label": "22",
          "value": "22"
        },
        {
          "label": "23",
          "value": "23"
        },
        {
          "label": "24",
          "value": "24"
        },
        {
          "label": "25",
          "value": "25"
        },
        {
          "label": "26",
          "value": "26"
        },
        {
          "label": "27",
          "value": "27"
        },
        {
          "label": "28",
          "value": "28"
        },
        {
          "label": "29",
          "value": "29"
        },
        {
          "label": "30",
          "value": "30"
        },
        {
          "label": "31",
          "value": "31"
        },
        {
          "label": "32",
          "value": "32"
        },
        {
          "label": "33",
          "value": "33"
        },
        {
          "label": "34",
          "value": "34"
        },
        {
          "label": "35",
          "value": "35"
        },
        {
          "label": "36",
          "value": "36"
        },
        {
          "label": "37",
          "value": "37"
        },
        {
          "label": "38",
          "value": "38"
        },
        {
          "label": "39",
          "value": "39"
        },
        {
          "label": "40",
          "value": "40"
        },
        {
          "label": "41",
          "value": "41"
        },
        {
          "label": "42",
          "value": "42"
        },
        {
          "label": "43",
          "value": "43"
        },
        {
          "label": "44",
          "value": "44"
        },
        {
          "label": "45",
          "value": "45"
        },
        {
          "label": "46",
          "value": "46"
        },
        {
          "label": "47",
          "value": "47"
        },
        {
          "label": "48",
          "value": "48"
        },
        {
          "label": "49",
          "value": "49"
        },
        {
          "label": "50",
          "value": "50"
        },
        {
          "label": "51",
          "value": "51"
        },
        {
          "label": "52",
          "value": "52"
        },
        {
          "label": "53",
          "value": "53"
        },
        {
          "label": "54",
          "value": "54"
        },
        {
          "label": "55",
          "value": "55"
        },
        {
          "label": "56",
          "value": "56"
        },
        {
          "label": "57",
          "value": "57"
        },
        {
          "label": "58",
          "value": "58"
        },
        {
          "label": "59",
          "value": "59"
        },
        {
          "label": "60",
          "value": "60"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_button_create_917\"><field name=\"CORNER\">CORNER_LEFT_UPPER</field><field name=\"FONT_SIZE\">7</field></block>"
}
```
