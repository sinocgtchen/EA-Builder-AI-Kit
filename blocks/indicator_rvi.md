# indicator_rvi

RVI 指標 商品 時間週期 平均週期 模式 K棒前移 位置

取得 相對活力指數指標 數值 (The Relative Vigor Index).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_rvi",
  "title": "RVI 指標 商品 時間週期 平均週期 模式 K棒前移 位置",
  "tooltip": "取得 相對活力指數指標 數值 (The Relative Vigor Index).",
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
      "name": "MODE_INDEX",
      "value": "MODE_MAIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線",
          "value": "MODE_MAIN"
        },
        {
          "label": "信號線",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_rvi\"><field name=\"MODE_INDEX\">MODE_MAIN</field></block>"
}
```
