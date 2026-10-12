# lists_Get_Maximum

陣列內容最大數值位置 陣列

取得陣列內容最大數值位置,陣列內容必須是數值

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "lists_Get_Maximum",
  "title": "陣列內容最大數值位置 陣列",
  "tooltip": "取得陣列內容最大數值位置,陣列內容必須是數值",
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
      "name": "LIST",
      "kind": "value",
      "connectionChecks": [
        "Array"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"lists_Get_Maximum\"></block>"
}
```
