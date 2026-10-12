# lists_setSize

陣列 設定長度

設定陣列長度

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_setSize",
  "title": "陣列 設定長度",
  "tooltip": "設定陣列長度",
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
      "name": "VALUE",
      "kind": "value",
      "connectionChecks": [
        "Array"
      ]
    },
    {
      "name": "SIZE_VALUE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_setSize\"></block>"
}
```
