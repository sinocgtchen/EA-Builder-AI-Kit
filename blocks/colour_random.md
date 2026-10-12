# colour_random

隨機顏色

隨機選擇一種顏色。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "colour_random",
  "title": "隨機顏色",
  "tooltip": "隨機選擇一種顏色。",
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
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Colour"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"colour_random\"></block>"
}
```
