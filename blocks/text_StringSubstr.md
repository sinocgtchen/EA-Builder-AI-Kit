# text_StringSubstr

回傳子字串 自字串 取得一段字串從位置 字串長度

返回指定的部分文字。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_StringSubstr",
  "title": "回傳子字串 自字串 取得一段字串從位置 字串長度",
  "tooltip": "返回指定的部分文字。",
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
      "name": "STRING",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "STR_FROM",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "STR_LENGTH",
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
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_StringSubstr\"></block>"
}
```
