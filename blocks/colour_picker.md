# colour_picker



從調色板中選擇一種顏色。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "colour_picker",
  "title": "",
  "tooltip": "從調色板中選擇一種顏色。",
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
      "name": "COLOUR",
      "value": "#ff0000",
      "kind": "field",
      "options": null
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Colour"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"colour_picker\"><field name=\"COLOUR\">#ff0000</field></block>"
}
```
