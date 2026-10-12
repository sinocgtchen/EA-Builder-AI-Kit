# indicator_sar

Parabolic SAR指標 商品 時間週期 加速因子(STEP) 最大值(MAX STEP) K棒前移 位置

取得 拋物線指標 數值 (Parabolic Stop and Reverse system).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_sar",
  "title": "Parabolic SAR指標 商品 時間週期 加速因子(STEP) 最大值(MAX STEP) K棒前移 位置",
  "tooltip": "取得 拋物線指標 數值 (Parabolic Stop and Reverse system).",
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
      "name": "STEP",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "MAX_STEP",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
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
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_sar\"></block>"
}
```
