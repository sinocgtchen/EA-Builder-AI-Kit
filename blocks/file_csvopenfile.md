# file_csvopenfile

開啟檔案(回傳檔案代碼) 檔案名稱 分隔符號

開啟一個新或舊檔案回傳檔案控制代碼,檔案將存在 Terminal>Common>Files

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_csvopenfile",
  "title": "開啟檔案(回傳檔案代碼) 檔案名稱 分隔符號",
  "tooltip": "開啟一個新或舊檔案回傳檔案控制代碼,檔案將存在 Terminal>Common>Files",
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
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "DELIMITER",
      "value": ",",
      "kind": "dropdown",
      "options": [
        {
          "label": ",",
          "value": ","
        },
        {
          "label": ";",
          "value": ";"
        },
        {
          "label": "#",
          "value": "#"
        },
        {
          "label": "@",
          "value": "@"
        },
        {
          "label": " ",
          "value": " "
        },
        {
          "label": ":",
          "value": ":"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_csvopenfile\"><field name=\"DELIMITER\">,</field></block>"
}
```
