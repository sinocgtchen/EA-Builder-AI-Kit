# variables_set_dynamic

賦值 為

設定此變數，好和輸入值相等。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "variables_set_dynamic",
  "title": "賦值 為",
  "tooltip": "設定此變數，好和輸入值相等。",
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
      "name": "VALUE",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"variables_set_dynamic\"><field name=\"VAR\" id=\"var-19b5ded2381d\">變數</field></block>"
}
```
