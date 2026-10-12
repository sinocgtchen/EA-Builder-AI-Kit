# text_append

在字串 後加入文字

將一些文字追加到變數。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_append",
  "title": "在字串 後加入文字",
  "tooltip": "將一些文字追加到變數。",
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
      "name": "TEXT",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "VAR",
      "value": "",
      "kind": "variable",
      "options": null
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_append\"><field name=\"VAR\" id=\"var-19b5ded2381d\">變數</field></block>"
}
```
