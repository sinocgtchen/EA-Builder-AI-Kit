# edit_object_data_get_917

取得編輯欄位資料 編號 回傳 型別

在圖表上取得編輯欄位資料(ObjectGetString)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "edit_object_data_get_917",
  "title": "取得編輯欄位資料 編號 回傳 型別",
  "tooltip": "在圖表上取得編輯欄位資料(ObjectGetString)",
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
      "name": "TYPE_INFO",
      "value": "Double",
      "kind": "dropdown",
      "options": [
        {
          "label": "小數(double)",
          "value": "Double"
        },
        {
          "label": "整數(int)",
          "value": "Integer"
        },
        {
          "label": "字串(string)",
          "value": "String"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"edit_object_data_get_917\"><field name=\"TYPE_INFO\">Double</field></block>"
}
```
