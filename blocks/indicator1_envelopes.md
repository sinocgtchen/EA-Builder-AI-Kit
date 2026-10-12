# indicator1_envelopes

Envelopes指標 商品 時間週期 平均週期 偏差值 MA方式 應用價格 模式 K棒前移 位置

取得 軌道線指標 數值 (The Envelopes)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator1_envelopes",
  "title": "Envelopes指標 商品 時間週期 平均週期 偏差值 MA方式 應用價格 模式 K棒前移 位置",
  "tooltip": "取得 軌道線指標 數值 (The Envelopes)",
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
      "name": "PERIOD",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "DEVIATION",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "IMA_METHODS",
      "kind": "value",
      "connectionChecks": null
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
      "name": "MODE",
      "value": "MODE_MAIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線(MT4)",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator1_envelopes\"><field name=\"MODE\">MODE_MAIN</field></block>"
}
```
