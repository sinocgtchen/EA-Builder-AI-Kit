# TesterHideIndicators

回測時隱藏指標

EA回測時隱藏指標,EA回測結束需要恢復設定

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "TesterHideIndicators",
  "title": "回測時隱藏指標",
  "tooltip": "EA回測時隱藏指標,EA回測結束需要恢復設定",
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
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"TesterHideIndicators\"></block>"
}
```
