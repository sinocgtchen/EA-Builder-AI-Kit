# logic_negate

非

如果輸入的值是 否，則返回 真。如果輸入的值是 真 返回 否。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "logic_negate",
  "title": "非",
  "tooltip": "如果輸入的值是 否，則返回 真。如果輸入的值是 真 返回 否。",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "BOOL",
      "kind": "value",
      "connectionChecks": [
        "Boolean"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"logic_negate\"></block>"
}
```
