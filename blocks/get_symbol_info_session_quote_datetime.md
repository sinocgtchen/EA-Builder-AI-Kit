# get_symbol_info_session_quote_datetime

取得商品開放報價時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間

回傳商品開放報價時段 SymbolInfoSessionQuote()相關資料, 回傳型別為 datetime

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_symbol_info_session_quote_datetime",
  "title": "取得商品開放報價時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間",
  "tooltip": "回傳商品開放報價時段 SymbolInfoSessionQuote()相關資料, 回傳型別為 datetime",
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
    },
    {
      "name": "CURRENCY_PAIR",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    },
    {
      "name": "",
      "kind": "dummy",
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
      "name": "ENUM_DAY_OF_WEEK",
      "value": "MONDAY",
      "kind": "dropdown",
      "options": [
        {
          "label": "星期一",
          "value": "MONDAY"
        },
        {
          "label": "星期二",
          "value": "TUESDAY"
        },
        {
          "label": "星期三",
          "value": "WEDNESDAY"
        },
        {
          "label": "星期四",
          "value": "THURSDAY"
        },
        {
          "label": "星期五",
          "value": "FRIDAY"
        },
        {
          "label": "星期六",
          "value": "SATURDAY"
        },
        {
          "label": "星期日",
          "value": "SUNDAY"
        }
      ]
    },
    {
      "name": "SESSION_INDEX",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
        {
          "label": "1",
          "value": "1"
        },
        {
          "label": "2",
          "value": "2"
        },
        {
          "label": "3",
          "value": "3"
        }
      ]
    },
    {
      "name": "TIME_FROM_TO",
      "value": "1",
      "kind": "dropdown",
      "options": [
        {
          "label": "開始",
          "value": "1"
        },
        {
          "label": "結束",
          "value": "2"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_symbol_info_session_quote_datetime\"><field name=\"ENUM_DAY_OF_WEEK\">MONDAY</field><field name=\"SESSION_INDEX\">0</field><field name=\"TIME_FROM_TO\">1</field></block>"
}
```
