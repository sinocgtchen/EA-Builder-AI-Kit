# lists_fill

陣列重複填滿數值 陣列 數值

陣列重複填滿數值

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_fill",
  "title": "陣列重複填滿數值 陣列 數值",
  "tooltip": "陣列重複填滿數值",
  "offeredInToolbox": {
    "ea": true,
    "script": false
  },
  "generatorAvailable": {
    "mt4": true,
    "mt5": true,
    "mt4script": false,
    "mt5script": false
  },
  "inputs": [
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "LIST",
      "kind": "value",
      "connectionChecks": [
        "Array"
      ]
    },
    {
      "name": "VALUE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_fill\"></block>"
}
```
