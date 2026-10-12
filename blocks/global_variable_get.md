# global_variable_get

取得總體(終端)變數 變數名稱

取得總體(終端)變數,當EA或電腦不預期當機,數值依然存在!

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "global_variable_get",
  "title": "取得總體(終端)變數 變數名稱",
  "tooltip": "取得總體(終端)變數,當EA或電腦不預期當機,數值依然存在!",
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
      "name": "VARIABLE_NAME",
      "kind": "value",
      "connectionChecks": null
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"global_variable_get\"></block>"
}
```
