# get_bar_size

取得K棒長度 商品 時間週期 K棒前移 位置

取得K棒長度

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_bar_size",
  "title": "取得K棒長度 商品 時間週期 K棒前移 位置",
  "tooltip": "取得K棒長度",
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
      "name": "KBAR_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "實體長度",
          "value": "0"
        },
        {
          "label": "上影線長度",
          "value": "1"
        },
        {
          "label": "下影線長度",
          "value": "2"
        },
        {
          "label": "總長度",
          "value": "3"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_bar_size\"><field name=\"KBAR_TYPE\">0</field></block>"
}
```
