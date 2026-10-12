# procedures_ifreturn

如果 回傳

如果值為 真，則返回第二個值。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "procedures_ifreturn",
  "title": "如果 回傳",
  "tooltip": "如果值為 真，則返回第二個值。",
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
      "name": "CONDITION",
      "kind": "value",
      "connectionChecks": [
        "Boolean"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"procedures_ifreturn\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" value=\"1\"></mutation></block>"
}
```
