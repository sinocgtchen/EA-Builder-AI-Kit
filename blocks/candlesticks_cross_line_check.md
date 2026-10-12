# candlesticks_cross_line_check

是否價格穿越指標 商品 時間週期 穿越方式 指標數值

價格穿越指標如 向上穿越 向下穿越

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "candlesticks_cross_line_check",
  "title": "是否價格穿越指標 商品 時間週期 穿越方式 指標數值",
  "tooltip": "價格穿越指標如 向上穿越 向下穿越",
  "offeredInToolbox": {
    "ea": false,
    "script": false
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
      "name": "INDICATOR_LINE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "TYPE_CROSS",
      "value": "1",
      "kind": "dropdown",
      "options": [
        {
          "label": "crossup",
          "value": "1"
        },
        {
          "label": "crossdown",
          "value": "2"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"candlesticks_cross_line_check\"><field name=\"TYPE_CROSS\">1</field></block>"
}
```
