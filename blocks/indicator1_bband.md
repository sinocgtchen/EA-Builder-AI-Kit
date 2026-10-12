# indicator1_bband

布林通道指標 商品 時間週期 平均週期 偏差值 應用價格 模式 K棒前移 位置



支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator1_bband",
  "title": "布林通道指標 商品 時間週期 平均週期 偏差值 應用價格 模式 K棒前移 位置",
  "tooltip": "",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "AP_PRICES",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator1_bband\"><field name=\"BAND_MODE\">MODE_MAIN</field></block>"
}
```
