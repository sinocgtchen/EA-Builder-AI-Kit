# indicator_bband

布林通道指標 商品 時間週期 平均週期 偏差值 應用價格 模式 K棒前移 位置



支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_bband",
  "title": "布林通道指標 商品 時間週期 平均週期 偏差值 應用價格 模式 K棒前移 位置",
  "tooltip": "",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "BAND_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "BAND_DEVIATION",
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
    }
  ],
  "fields": [
    {
      "name": "PRICE",
      "value": "PRICE_CLOSE",
      "kind": "dropdown",
      "options": [
        {
          "label": "收盤價",
          "value": "PRICE_CLOSE"
        },
        {
          "label": "開盤價",
          "value": "PRICE_OPEN"
        },
        {
          "label": "高價",
          "value": "PRICE_HIGH"
        },
        {
          "label": "低價",
          "value": "PRICE_LOW"
        },
        {
          "label": "中間價",
          "value": "PRICE_MEDIAN"
        },
        {
          "label": "典型價格",
          "value": "PRICE_TYPICAL"
        },
        {
          "label": "平均價格",
          "value": "PRICE_WEIGHTED"
        }
      ]
    },
    {
      "name": "BAND_MODE",
      "value": "MODE_MAIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線",
          "value": "MODE_MAIN"
        },
        {
          "label": "上緣線",
          "value": "MODE_UPPER"
        },
        {
          "label": "下緣線",
          "value": "MODE_LOWER"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_bband\"><field name=\"PRICE\">PRICE_CLOSE</field><field name=\"BAND_MODE\">MODE_MAIN</field></block>"
}
```
