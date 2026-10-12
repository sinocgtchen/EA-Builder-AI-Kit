# indicator1_adx

ADX 指標 商品 時間週期 平均週期 模式 應用價格 K棒前移 位置

取得 動向指標 數值 (The Average Directional Movement Index indicator).

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator1_adx",
  "title": "ADX 指標 商品 時間週期 平均週期 模式 應用價格 K棒前移 位置",
  "tooltip": "取得 動向指標 數值 (The Average Directional Movement Index indicator).",
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
      "name": "AP_PRICES",
      "kind": "value",
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
      "name": "MODE_LINE_INDEX",
      "value": "MODE_MAIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線",
          "value": "MODE_MAIN"
        },
        {
          "label": "+DI線",
          "value": "MODE_PLUSDI"
        },
        {
          "label": "-DI線",
          "value": "MODE_MINUSDI"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator1_adx\"><field name=\"MODE_LINE_INDEX\">MODE_MAIN</field></block>"
}
```
