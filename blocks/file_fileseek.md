# file_fileseek

設定讀寫檔案位置(回傳真/否) 檔案代碼 位移 讀寫位置

讀寫檔案位置設定,如果設定成功回傳 真 否則回傳 否

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_fileseek",
  "title": "設定讀寫檔案位置(回傳真/否) 檔案代碼 位移 讀寫位置",
  "tooltip": "讀寫檔案位置設定,如果設定成功回傳 真 否則回傳 否",
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
      "name": "FILE_OFFSET",
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
      "name": "FILE_POSITION",
      "value": "SEEK_SET",
      "kind": "dropdown",
      "options": [
        {
          "label": "檔案起點",
          "value": "SEEK_SET"
        },
        {
          "label": "目前位置",
          "value": "SEEK_CUR"
        },
        {
          "label": "檔案末尾",
          "value": "SEEK_END"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_fileseek\"><field name=\"FILE_POSITION\">SEEK_SET</field></block>"
}
```
