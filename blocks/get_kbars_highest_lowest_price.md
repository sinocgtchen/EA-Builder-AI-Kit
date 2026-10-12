# get_kbars_highest_lowest_price

取得K棒 商品 時間週期 型別 K棒前移 到

取得K棒最高/最低價格.

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_kbars_highest_lowest_price",
  "title": "取得K棒 商品 時間週期 型別 K棒前移 到",
  "tooltip": "取得K棒最高/最低價格.",
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
      "name": "KBAR_FROM",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "KBAR_COUNT",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "HL_PRICE",
      "value": "iHighest",
      "kind": "dropdown",
      "options": [
        {
          "label": "最高價格",
          "value": "iHighest"
        },
        {
          "label": "最低價格",
          "value": "iLowest"
        }
      ]
    },
    {
      "name": "TIMESERIES",
      "value": "MODE_OPEN",
      "kind": "dropdown",
      "options": [
        {
          "label": "開盤價",
          "value": "MODE_OPEN"
        },
        {
          "label": "最低價",
          "value": "MODE_LOW"
        },
        {
          "label": "最高價",
          "value": "MODE_HIGH"
        },
        {
          "label": "收盤價",
          "value": "MODE_CLOSE"
        },
        {
          "label": "報價量",
          "value": "MODE_VOLUME"
        },
        {
          "label": "真實交易量(MT5)",
          "value": "MODE_REAL_VOLUME"
        },
        {
          "label": "點差(MT5)",
          "value": "MODE_SPREAD"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_kbars_highest_lowest_price\"><field name=\"HL_PRICE\">iHighest</field><field name=\"TIMESERIES\">MODE_OPEN</field></block>"
}
```
