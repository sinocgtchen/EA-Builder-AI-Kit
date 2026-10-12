# objects_delete_917

刪除物件 名稱 編號

刪除圖標上的物件

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "objects_delete_917",
  "title": "刪除物件 名稱 編號",
  "tooltip": "刪除圖標上的物件",
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
    }
  ],
  "fields": [
    {
      "name": "OBJECTS",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "標籤物件",
          "value": "0"
        },
        {
          "label": "按鈕物件",
          "value": "1"
        },
        {
          "label": "編輯欄位",
          "value": "2"
        },
        {
          "label": "複選框",
          "value": "3"
        },
        {
          "label": "圖片物件",
          "value": "4"
        },
        {
          "label": "面板物件",
          "value": "5"
        },
        {
          "label": "矩形物件",
          "value": "6"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"objects_delete_917\"><field name=\"OBJECTS\">0</field></block>"
}
```
