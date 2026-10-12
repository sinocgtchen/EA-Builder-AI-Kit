# get_bar_price

取得K棒價格 商品 時間週期 K棒前移 位置

取得K棒價格

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_bar_price",
  "title": "取得K棒價格 商品 時間週期 K棒前移 位置",
  "tooltip": "取得K棒價格",
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
      "name": "MODE_PRICE",
      "value": "iClose",
      "kind": "dropdown",
      "options": [
        {
          "label": "收盤價",
          "value": "iClose"
        },
        {
          "label": "開盤價",
          "value": "iOpen"
        },
        {
          "label": "高價",
          "value": "iHigh"
        },
        {
          "label": "低價",
          "value": "iLow"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_bar_price\"><field name=\"MODE_PRICE\">iClose</field></block>"
}
```
