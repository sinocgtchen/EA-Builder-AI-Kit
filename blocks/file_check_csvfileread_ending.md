# file_check_csvfileread_ending

是否檔案資料讀取到最後 檔案代碼

檔案讀取到最後時回傳true,否則回傳false

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_check_csvfileread_ending",
  "title": "是否檔案資料讀取到最後 檔案代碼",
  "tooltip": "檔案讀取到最後時回傳true,否則回傳false",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_check_csvfileread_ending\"></block>"
}
```
