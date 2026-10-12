# indicator_kd

KD隨機指標 商品 時間週期 K週期 D週期 減速值 MA方式 應用價格 模式 K棒前移 位置

取得 KD隨機指標 數值 (The Stochastic Oscillator).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_kd",
  "title": "KD隨機指標 商品 時間週期 K週期 D週期 減速值 MA方式 應用價格 模式 K棒前移 位置",
  "tooltip": "取得 KD隨機指標 數值 (The Stochastic Oscillator).",
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
      "name": "K_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "D_PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "SLOWING",
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
      "value": "STO_LOWHIGH",
      "kind": "dropdown",
      "options": [
        {
          "label": "最低價/最高價計算",
          "value": "STO_LOWHIGH"
        },
        {
          "label": "開盤價/收盤價計算",
          "value": "STO_CLOSECLOSE"
        }
      ]
    },
    {
      "name": "MODE_INDEX",
      "value": "MODE_MAIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線(快線)",
          "value": "MODE_MAIN"
        },
        {
          "label": "訊號線(慢線)",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_kd\"><field name=\"METHOD\">MODE_SMA</field><field name=\"AP_PRICE\">STO_LOWHIGH</field><field name=\"MODE_INDEX\">MODE_MAIN</field></block>"
}
```
