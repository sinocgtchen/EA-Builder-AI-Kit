# mql_onTester

優化自定義績效函數OnTester() 回傳

用於評估測試結果的自定義標準優化數值

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "mql_onTester",
  "title": "優化自定義績效函數OnTester() 回傳",
  "tooltip": "用於評估測試結果的自定義標準優化數值",
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
      "name": "OnTesterStatement",
      "kind": "statement",
      "connectionChecks": null
    },
    {
      "name": "RETURN",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TYPE",
      "value": "double",
      "kind": "dropdown",
      "options": [
        {
          "label": "double",
          "value": "double"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"mql_onTester\"><field name=\"TYPE\">double</field></block>"
}
```
