# chart_open

開啟指定商品圖表 商品 時間週期

開啟指定的商品圖表及週期,如果開啟成功回傳圖表編號,否則回傳0

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "chart_open",
  "title": "開啟指定商品圖表 商品 時間週期",
  "tooltip": "開啟指定的商品圖表及週期,如果開啟成功回傳圖表編號,否則回傳0",
  "offeredInToolbox": {
    "ea": true,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": false,
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
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"chart_open\"></block>"
}
```
