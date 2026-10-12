# Server_is_Connected

檢查是否與伺服器連線中

檢查網路是否與眷商伺服器連線中

支援產生器：mt4, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "Server_is_Connected",
  "title": "檢查是否與伺服器連線中",
  "tooltip": "檢查網路是否與眷商伺服器連線中",
  "offeredInToolbox": {
    "ea": true,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": false,
    "mt4script": true,
    "mt5script": true
  },
  "inputs": [
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"Server_is_Connected\"></block>"
}
```
