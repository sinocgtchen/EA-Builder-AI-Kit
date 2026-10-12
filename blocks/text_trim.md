# text_trim



複製這段文字的同時刪除兩端多餘的空格。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_trim",
  "title": "",
  "tooltip": "複製這段文字的同時刪除兩端多餘的空格。",
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
      "name": "TEXT",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    }
  ],
  "fields": [
    {
      "name": "MODE",
      "value": "BOTH",
      "kind": "dropdown",
      "options": [
        {
          "label": "消除兩側空格",
          "value": "BOTH"
        },
        {
          "label": "消除左側空格",
          "value": "LEFT"
        },
        {
          "label": "消除右側空格",
          "value": "RIGHT"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_trim\"><field name=\"MODE\">BOTH</field></block>"
}
```
