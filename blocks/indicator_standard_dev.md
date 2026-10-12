# indicator_standard_dev

標準偏差指標 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置

取得 標準偏差指標 數值 (The Standard Deviation).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_standard_dev",
  "title": "標準偏差指標 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置",
  "tooltip": "取得 標準偏差指標 數值 (The Standard Deviation).",
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
      "name": "IMA_PERIOD",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_standard_dev\"><field name=\"METHOD\">MODE_SMA</field><field name=\"AP_PRICE\">PRICE_CLOSE</field></block>"
}
```
