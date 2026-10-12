# text_changeCase

轉成

使用不同的大小寫複製這段文字。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_changeCase",
  "title": "轉成",
  "tooltip": "使用不同的大小寫複製這段文字。",
  "offeredInToolbox": {
    "ea": true,
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
      "name": "SRC_STRING",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    }
  ],
  "fields": [
    {
      "name": "CASE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "大寫",
          "value": "0"
        },
        {
          "label": "小寫",
          "value": "1"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_changeCase\"><field name=\"CASE\">0</field></block>"
}
```
