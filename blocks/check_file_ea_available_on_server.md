# check_file_ea_available_on_server

雲端檔案內EA是否授權 KEY(授權碼) 檔案(表格)名稱 EA編號(ID)

檢查檔案內EA是否在有效期內及相關對應網站資訊,須配合MT4EAcheck.dll/MT5EAcheck.dll檔案.

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_file_ea_available_on_server",
  "title": "雲端檔案內EA是否授權 KEY(授權碼) 檔案(表格)名稱 EA編號(ID)",
  "tooltip": "檢查檔案內EA是否在有效期內及相關對應網站資訊,須配合MT4EAcheck.dll/MT5EAcheck.dll檔案.",
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
      "name": "USER_TOKEN",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "EA_FILE_NAME",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "EA_ID",
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
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_file_ea_available_on_server\"></block>"
}
```
