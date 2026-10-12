# get_applied_price



技術指標的計算要求價格

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_applied_price",
  "title": "",
  "tooltip": "技術指標的計算要求價格",
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
    }
  ],
  "fields": [
    {
      "name": "APPLIED_PRICE",
      "value": "PRICE_CLOSE",
      "kind": "dropdown",
      "options": [
        {
          "label": "收盤價",
          "value": "PRICE_CLOSE"
        },
        {
          "label": "開盤價",
          "value": "PRICE_OPEN"
        },
        {
          "label": "高價",
          "value": "PRICE_HIGH"
        },
        {
          "label": "低價",
          "value": "PRICE_LOW"
        },
        {
          "label": "中間價",
          "value": "PRICE_MEDIAN"
        },
        {
          "label": "典型價格",
          "value": "PRICE_TYPICAL"
        },
        {
          "label": "平均價格",
          "value": "PRICE_WEIGHTED"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_applied_price\"><field name=\"APPLIED_PRICE\">PRICE_CLOSE</field></block>"
}
```
