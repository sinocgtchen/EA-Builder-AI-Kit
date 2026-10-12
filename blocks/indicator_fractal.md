# indicator_fractal

分形指標 商品 時間週期 模式 K棒前移 位置

取得 分形指標 數值 (The Fractals indicator).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_fractal",
  "title": "分形指標 商品 時間週期 模式 K棒前移 位置",
  "tooltip": "取得 分形指標 數值 (The Fractals indicator).",
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
      "name": "LINE_MODE",
      "value": "MODE_UPPER",
      "kind": "dropdown",
      "options": [
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_fractal\"><field name=\"LINE_MODE\">MODE_UPPER</field></block>"
}
```
