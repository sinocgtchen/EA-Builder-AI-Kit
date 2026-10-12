# lists_sort_ascend

陣列內容由小到大排序 陣列

陣列內容由小到大排序

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_sort_ascend",
  "title": "陣列內容由小到大排序 陣列",
  "tooltip": "陣列內容由小到大排序",
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
      "name": "LIST",
      "kind": "value",
      "connectionChecks": [
        "Array"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_sort_ascend\"></block>"
}
```
