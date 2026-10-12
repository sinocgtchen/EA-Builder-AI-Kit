# indicator_ichimoku

Ichimoku指標 商品 時間週期 Tenkan Sen週期 Kijun Sen週期 Senkou SpanB週期 模式 K棒前移 位置

取得 一目均衡表指標 數值 (the Ichimoku Kinko Hyo).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_ichimoku",
  "title": "Ichimoku指標 商品 時間週期 Tenkan Sen週期 Kijun Sen週期 Senkou SpanB週期 模式 K棒前移 位置",
  "tooltip": "取得 一目均衡表指標 數值 (the Ichimoku Kinko Hyo).",
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
      "name": "TENKAN_SEN",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "KIJUN_SEN",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "SENKOU_SPAN_B",
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
      "name": "MODE",
      "value": "MODE_TENKANSEN",
      "kind": "dropdown",
      "options": [
        {
          "label": "MODE_TENKANSEN",
          "value": "MODE_TENKANSEN"
        },
        {
          "label": "MODE_KIJUNSEN",
          "value": "MODE_KIJUNSEN"
        },
        {
          "label": "MODE_SENKOUSPANA",
          "value": "MODE_SENKOUSPANA"
        },
        {
          "label": "MODE_SENKOUSPANB",
          "value": "MODE_SENKOUSPANB"
        },
        {
          "label": "MODE_CHIKOUSPAN",
          "value": "MODE_CHIKOUSPAN"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_ichimoku\"><field name=\"MODE\">MODE_TENKANSEN</field></block>"
}
```
