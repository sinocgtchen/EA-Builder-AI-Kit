# object_checkbox_917

建立複選框 編號 顯示文字 水平位置 垂直位置 寬度 顏色

打勾表示選取,不打勾表示不選取

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_checkbox_917",
  "title": "建立複選框 編號 顯示文字 水平位置 垂直位置 寬度 顏色",
  "tooltip": "打勾表示選取,不打勾表示不選取",
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
      "name": "DISPLAY_INFO",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "X_DISTANCE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "Y_DISTANCE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "TEXT_WIDTH",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "ARROW_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_checkbox_917\"></block>"
}
```
