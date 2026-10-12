# global_variable_set

總體(終端)變數設定 變數名稱 數值

總體(終端)變數設定,當EA或電腦不預期當機,數值依然存在!

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "global_variable_set",
  "title": "總體(終端)變數設定 變數名稱 數值",
  "tooltip": "總體(終端)變數設定,當EA或電腦不預期當機,數值依然存在!",
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
    },
    {
      "name": "VARIABLE_VALUE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"global_variable_set\"></block>"
}
```
