# indicator_macd

MACD 指標 商品 時間週期 快速週期 慢速週期 訊號週期 應用價格 模式 K棒前移 位置

取得 MACD指標 數值(Moving Averages Convergence/Divergence indicator)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_macd",
  "title": "MACD 指標 商品 時間週期 快速週期 慢速週期 訊號週期 應用價格 模式 K棒前移 位置",
  "tooltip": "取得 MACD指標 數值(Moving Averages Convergence/Divergence indicator)",
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
      "name": "FAST_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "SLOW_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "SIGNAL_PERIOD",
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
      "name": "AP_PRICE",
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
      "name": "MODE_INDEX",
      "value": "MODE_MAIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線(柱形)",
          "value": "MODE_MAIN"
        },
        {
          "label": "訊號線(線形)",
          "value": "MODE_SIGNAL"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_macd\"><field name=\"AP_PRICE\">PRICE_CLOSE</field><field name=\"MODE_INDEX\">MODE_MAIN</field></block>"
}
```
