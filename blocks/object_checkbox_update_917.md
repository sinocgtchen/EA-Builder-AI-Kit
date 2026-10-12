# object_checkbox_update_917

更新複選框狀態 編號 狀態

更新複選框設定

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "object_checkbox_update_917",
  "title": "更新複選框狀態 編號 狀態",
  "tooltip": "更新複選框設定",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "CHECKBOX_STATUS",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "不選",
          "value": "0"
        },
        {
          "label": "選擇",
          "value": "1"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"object_checkbox_update_917\"><field name=\"CHECKBOX_STATUS\">0</field></block>"
}
```
