# lists_indexOf

陣列 找出 項目出現

返回在陣列中的第一個/最後一個匹配項目的索引值。如果未找到則返回 0。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_indexOf",
  "title": "陣列 找出 項目出現",
  "tooltip": "返回在陣列中的第一個/最後一個匹配項目的索引值。如果未找到則返回 0。",
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
      "connectionChecks": [
        "Array"
      ]
    },
    {
      "name": "FIND",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "END",
      "value": "FIRST",
      "kind": "dropdown",
      "options": [
        {
          "label": "第一個",
          "value": "FIRST"
        },
        {
          "label": "最後一個",
          "value": "LAST"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_indexOf\"><field name=\"END\">FIRST</field></block>"
}
```
