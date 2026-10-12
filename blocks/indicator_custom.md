# indicator_custom

自定義指標 商品 時間週期 指標名稱 資料索引值 K棒前移 位置

取得 自定義指標 數值 (The Custom indicator).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_custom",
  "title": "自定義指標 商品 時間週期 指標名稱 資料索引值 K棒前移 位置",
  "tooltip": "取得 自定義指標 數值 (The Custom indicator).",
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
      "name": "CURRENCY_PAIR",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "TIMEFRAME",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "INDICATOR_NAME",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "KBAR_SHIFT",
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
      "name": "EMPTY",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "INDICATOR_MODE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
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
        },
        {
          "label": "6",
          "value": "6"
        },
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_custom\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" items=\"0\"></mutation><field name=\"INDICATOR_MODE\">0</field></block>"
}
```
