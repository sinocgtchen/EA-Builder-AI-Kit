# text_prompt

輸入 並顯示提示訊息

輸入文字

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_prompt",
  "title": "輸入 並顯示提示訊息",
  "tooltip": "輸入文字",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TYPE",
      "value": "TEXT",
      "kind": "dropdown",
      "options": [
        {
          "label": "文字",
          "value": "TEXT"
        },
        {
          "label": "數字",
          "value": "NUMBER"
        }
      ]
    },
    {
      "name": "TEXT",
      "value": "",
      "kind": "field",
      "options": null
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_prompt\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" type=\"TEXT\"></mutation><field name=\"TYPE\">TEXT</field><field name=\"TEXT\"></field></block>"
}
```
