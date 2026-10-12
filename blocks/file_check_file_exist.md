# file_check_file_exist

是否檔案存在 檔案名稱

檢查檔案是否已存在,如果存在回傳真,否則回傳否

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_check_file_exist",
  "title": "是否檔案存在 檔案名稱",
  "tooltip": "檢查檔案是否已存在,如果存在回傳真,否則回傳否",
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
    },
    {
      "name": "FILENAME",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_check_file_exist\"></block>"
}
```
