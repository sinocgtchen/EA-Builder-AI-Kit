# get_comments_by_ticket

依單號取得註解 單號 型別

依單號取得註解資料,部位:已進場部位,掛單:目前已掛單

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_comments_by_ticket",
  "title": "依單號取得註解 單號 型別",
  "tooltip": "依單號取得註解資料,部位:已進場部位,掛單:目前已掛單",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "ORDER_TICKET",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "TYPE_INFO",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "已進場部位",
          "value": "0"
        },
        {
          "label": "已進場掛單",
          "value": "1"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_comments_by_ticket\"><field name=\"TYPE_INFO\">0</field></block>"
}
```
