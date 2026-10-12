# text_getSubstring

自字串 到

返回指定的部分文字。

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "text_getSubstring",
  "title": "自字串 到",
  "tooltip": "返回指定的部分文字。",
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
      "name": "STRING",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "AT1",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "AT2",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [
    {
      "name": "WHERE1",
      "value": "FROM_START",
      "kind": "dropdown",
      "options": [
        {
          "label": "取得一段字串從位置",
          "value": "FROM_START"
        },
        {
          "label": "取得一段字串自 #",
          "value": "FROM_END"
        },
        {
          "label": "取得一段字串 自 第一個字元",
          "value": "FIRST"
        }
      ]
    },
    {
      "name": "WHERE2",
      "value": "FROM_START",
      "kind": "dropdown",
      "options": [
        {
          "label": "字元 #",
          "value": "FROM_START"
        },
        {
          "label": "倒數第 # 個字元",
          "value": "FROM_END"
        },
        {
          "label": "最後一個字元",
          "value": "LAST"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"text_getSubstring\"><mutation xmlns=\"http://www.w3.org/1999/xhtml\" at1=\"true\" at2=\"true\"></mutation><field name=\"WHERE1\">FROM_START</field><field name=\"WHERE2\">FROM_START</field></block>"
}
```
