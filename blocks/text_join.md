# text_join

建立字串使用

通過串起任意數量的項目來建立一段文字。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_join",
  "title": "建立字串使用",
  "tooltip": "通過串起任意數量的項目來建立一段文字。",
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
      "name": "ADD0",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "ADD1",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_join\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" items=\"2\"></mutation></block>"
}
```
