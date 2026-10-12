# indicator_mt5_ADXWilder

ADX Wilder指標(MT5) 商品 時間週期 平均週期 模式 K棒前移 位置

Average Directional Movement Index by Welles Wilder.

支援產生器：mt4, mt5, mt4script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicator_mt5_ADXWilder",
  "title": "ADX Wilder指標(MT5) 商品 時間週期 平均週期 模式 K棒前移 位置",
  "tooltip": "Average Directional Movement Index by Welles Wilder.",
  "offeredInToolbox": {
    "ea": true,
    "script": true
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": true,
    "mt5script": false
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
      "value": "MAIN_LINE",
      "kind": "dropdown",
      "options": [
        {
          "label": "主線",
          "value": "MAIN_LINE"
        },
        {
          "label": "+DI線",
          "value": "PLUSDI_LINE"
        },
        {
          "label": "-DI線",
          "value": "MINUSDI_LINE"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicator_mt5_ADXWilder\"><field name=\"MODE_LINE_INDEX\">MAIN_LINE</field></block>"
}
```
