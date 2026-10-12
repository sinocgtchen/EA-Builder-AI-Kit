# indicator_obv

平衡交易量指標 商品 時間週期 應用價格 K棒前移 位置

取得 平衡交易量指標 數值 (The On Balance Volume indicator).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_obv",
  "title": "平衡交易量指標 商品 時間週期 應用價格 K棒前移 位置",
  "tooltip": "取得 平衡交易量指標 數值 (The On Balance Volume indicator).",
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
          "label": "收盤價(MT4)",
          "value": "PRICE_CLOSE"
        },
        {
          "label": "開盤價(MT4)",
          "value": "PRICE_OPEN"
        },
        {
          "label": "高價(MT4)",
          "value": "PRICE_HIGH"
        },
        {
          "label": "低價(MT4)",
          "value": "PRICE_LOW"
        },
        {
          "label": "中間價(MT4)",
          "value": "PRICE_MEDIAN"
        },
        {
          "label": "典型價格(MT4)",
          "value": "PRICE_TYPICAL"
        },
        {
          "label": "平均價格(MT4)",
          "value": "PRICE_WEIGHTED"
        },
        {
          "label": "Tick成交量(MT5)",
          "value": "VOLUME_TICK"
        },
        {
          "label": "Real成交量(MT5)",
          "value": "VOLUME_REAL"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_obv\"><field name=\"AP_PRICE\">PRICE_CLOSE</field></block>"
}
```
