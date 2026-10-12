# colour_rgb

顏色 紅 綠 藍

透過指定紅、綠、 藍色的值來建立一種顏色。所有的值必須介於 0 和 100 之間。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "colour_rgb",
  "title": "顏色 紅 綠 藍",
  "tooltip": "透過指定紅、綠、 藍色的值來建立一種顏色。所有的值必須介於 0 和 100 之間。",
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
      "name": "RED",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "GREEN",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "BLUE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"colour_rgb\"></block>"
}
```
