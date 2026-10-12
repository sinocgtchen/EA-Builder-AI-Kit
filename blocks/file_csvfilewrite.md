# file_csvfilewrite

寫入資料到檔案 檔案代碼 資料

寫入資料到檔案

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_csvfilewrite",
  "title": "寫入資料到檔案 檔案代碼 資料",
  "tooltip": "寫入資料到檔案",
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
      "name": "FILEHANDLE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "FILEDATA",
      "kind": "value",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_csvfilewrite\"></block>"
}
```
