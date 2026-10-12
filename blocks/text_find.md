# text_find

回傳字串的位置 在字串 從字元開始位置 欲搜尋子字串

回傳欲搜尋子字串的位置

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_find",
  "title": "回傳字串的位置 在字串 從字元開始位置 欲搜尋子字串",
  "tooltip": "回傳欲搜尋子字串的位置",
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
        "String"
      ]
    },
    {
      "name": "POS_START",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "FIND",
      "kind": "value",
      "connectionChecks": [
        "String"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_find\"></block>"
}
```
