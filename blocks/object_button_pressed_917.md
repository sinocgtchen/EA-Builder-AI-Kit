# object_button_pressed_917

按下按鈕執行 編號

按下按鈕執行框起來的動作

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_button_pressed_917",
  "title": "按下按鈕執行 編號",
  "tooltip": "按下按鈕執行框起來的動作",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "OBJECT_ID",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "BUTTON_STATE",
      "kind": "statement",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_button_pressed_917\"></block>"
}
```
