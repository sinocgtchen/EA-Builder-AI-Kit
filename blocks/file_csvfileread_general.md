# file_csvfileread_general

讀取檔案資料 檔案代碼 型別

讀取檔案資料

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_csvfileread_general",
  "title": "讀取檔案資料 檔案代碼 型別",
  "tooltip": "讀取檔案資料",
  "offeredInToolbox": {
    "ea": true,
    "script": false
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TYPE_INFO",
      "value": "Number",
      "kind": "dropdown",
      "options": [
        {
          "label": "double",
          "value": "Number"
        },
        {
          "label": "string",
          "value": "String"
        },
        {
          "label": "long",
          "value": "Long"
        },
        {
          "label": "datetime",
          "value": "Datetime"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_csvfileread_general\"><field name=\"TYPE_INFO\">Number</field></block>"
}
```
