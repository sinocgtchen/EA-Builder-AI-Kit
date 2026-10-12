# chart_close

關閉指定商品圖表 圖表編號

使用圖表編號關閉指定圖表,如果關閉成功回傳真(true),否則回傳否(false)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "chart_close",
  "title": "關閉指定商品圖表 圖表編號",
  "tooltip": "使用圖表編號關閉指定圖表,如果關閉成功回傳真(true),否則回傳否(false)",
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
      "name": "CHART_ID",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"chart_close\"></block>"
}
```
