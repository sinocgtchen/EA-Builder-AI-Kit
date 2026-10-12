# indicator_gator

鱷魚震盪指標 商品 時間週期 下颚週期(藍線) 下颚位移 牙齒週期(紅線) 牙齒位移 嘴唇週期(綠線) 嘴唇位移 MA方式 應用價格 模式 K棒前移 位置

取得 鱷魚震盪指標 數值 (The Gator oscillator indicator).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_gator",
  "title": "鱷魚震盪指標 商品 時間週期 下颚週期(藍線) 下颚位移 牙齒週期(紅線) 牙齒位移 嘴唇週期(綠線) 嘴唇位移 MA方式 應用價格 模式 K棒前移 位置",
  "tooltip": "取得 鱷魚震盪指標 數值 (The Gator oscillator indicator).",
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
      "name": "JAW_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "JAW_SHIFT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "TEETH_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "TEETH_SHIFT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "LIPS_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "LIPS_SHIFT",
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
      "name": "METHOD",
      "value": "MODE_SMA",
      "kind": "dropdown",
      "options": [
        {
          "label": "簡單平均數",
          "value": "MODE_SMA"
        },
        {
          "label": "指數平均數",
          "value": "MODE_EMA"
        },
        {
          "label": "平滑平均數",
          "value": "MODE_SMMA"
        },
        {
          "label": "線性平均數",
          "value": "MODE_LWMA"
        }
      ]
    },
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
      "name": "LINE_MODE",
      "value": "MODE_UPPER",
      "kind": "dropdown",
      "options": [
        {
          "label": "MODE_UPPER",
          "value": "MODE_UPPER"
        },
        {
          "label": "MODE_LOWER",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_gator\"><field name=\"METHOD\">MODE_SMA</field><field name=\"AP_PRICE\">PRICE_CLOSE</field><field name=\"LINE_MODE\">MODE_UPPER</field></block>"
}
```
