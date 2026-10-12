# file_chart_apply_template

在圖表中開啟指定模板(template) 圖表編號 模板名稱

在圖表中開啟指定特定模板(template),正常開起模板回傳true,否則回傳false

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "file_chart_apply_template",
  "title": "在圖表中開啟指定模板(template) 圖表編號 模板名稱",
  "tooltip": "在圖表中開啟指定特定模板(template),正常開起模板回傳true,否則回傳false",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "CHART_ID",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "FILENAME",
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
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"file_chart_apply_template\"></block>"
}
```
