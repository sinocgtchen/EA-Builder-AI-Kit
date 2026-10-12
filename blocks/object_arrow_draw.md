# object_arrow_draw

建立特殊符號 符號名稱 時間 價格 符號位置 符號碼 寬度 顏色

在圖表上畫上一個特殊符號

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_arrow_draw",
  "title": "建立特殊符號 符號名稱 時間 價格 符號位置 符號碼 寬度 顏色",
  "tooltip": "在圖表上畫上一個特殊符號",
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
      "name": "ARROW_NAME",
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
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "ARROW_POSITION",
      "value": "ANCHOR_TOP",
      "kind": "dropdown",
      "options": [
        {
          "label": "上面",
          "value": "ANCHOR_TOP"
        },
        {
          "label": "下面",
          "value": "ANCHOR_BOTTOM"
        }
      ]
    },
    {
      "name": "ARROW_CODE",
      "value": "5",
      "kind": "dropdown",
      "options": [
        {
          "label": "w5",
          "value": "5"
        },
        {
          "label": "w6",
          "value": "6"
        },
        {
          "label": "w38",
          "value": "38"
        },
        {
          "label": "w40",
          "value": "40"
        },
        {
          "label": "w69",
          "value": "69"
        },
        {
          "label": "w70",
          "value": "70"
        },
        {
          "label": "w71",
          "value": "71"
        },
        {
          "label": "w72",
          "value": "72"
        },
        {
          "label": "w74",
          "value": "74"
        },
        {
          "label": "w75",
          "value": "75"
        },
        {
          "label": "w76",
          "value": "76"
        },
        {
          "label": "w108",
          "value": "108"
        },
        {
          "label": "w140",
          "value": "140"
        },
        {
          "label": "w141",
          "value": "141"
        },
        {
          "label": "w142",
          "value": "142"
        },
        {
          "label": "w143",
          "value": "143"
        },
        {
          "label": "w144",
          "value": "144"
        },
        {
          "label": "w145",
          "value": "145"
        },
        {
          "label": "w146",
          "value": "146"
        },
        {
          "label": "w147",
          "value": "147"
        },
        {
          "label": "w148",
          "value": "148"
        },
        {
          "label": "w181",
          "value": "181"
        },
        {
          "label": "w231",
          "value": "231"
        },
        {
          "label": "w232",
          "value": "232"
        },
        {
          "label": "w233",
          "value": "233"
        },
        {
          "label": "w234",
          "value": "234"
        },
        {
          "label": "w235",
          "value": "235"
        },
        {
          "label": "w236",
          "value": "236"
        },
        {
          "label": "w237",
          "value": "237"
        },
        {
          "label": "w238",
          "value": "238"
        },
        {
          "label": "w239",
          "value": "239"
        },
        {
          "label": "w240",
          "value": "240"
        },
        {
          "label": "w241",
          "value": "241"
        },
        {
          "label": "w242",
          "value": "242"
        },
        {
          "label": "w243",
          "value": "243"
        },
        {
          "label": "w244",
          "value": "244"
        },
        {
          "label": "w245",
          "value": "245"
        },
        {
          "label": "w246",
          "value": "246"
        },
        {
          "label": "w247",
          "value": "247"
        },
        {
          "label": "w248",
          "value": "248"
        },
        {
          "label": "w251",
          "value": "251"
        },
        {
          "label": "w252",
          "value": "252"
        },
        {
          "label": "w1",
          "value": "1"
        },
        {
          "label": "w3",
          "value": "3"
        }
      ]
    },
    {
      "name": "ARROW_WIDTH",
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
          "label": "4",
          "value": "4"
        },
        {
          "label": "6",
          "value": "6"
        },
        {
          "label": "10",
          "value": "10"
        },
        {
          "label": "15",
          "value": "15"
        },
        {
          "label": "20",
          "value": "20"
        },
        {
          "label": "30",
          "value": "30"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_arrow_draw\"><field name=\"ARROW_POSITION\">ANCHOR_TOP</field><field name=\"ARROW_CODE\">5</field><field name=\"ARROW_WIDTH\">1</field></block>"
}
```
