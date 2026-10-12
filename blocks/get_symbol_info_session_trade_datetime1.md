# get_symbol_info_session_trade_datetime1

取得商品開放交易時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間

回傳商品開放交易時段 SymbolInfoSessionTrade()相關資料, 回傳型別為 datetime

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_symbol_info_session_trade_datetime1",
  "title": "取得商品開放交易時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間",
  "tooltip": "回傳商品開放交易時段 SymbolInfoSessionTrade()相關資料, 回傳型別為 datetime",
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
      "name": "CURRENCY_PAIR",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "ENUM_DAY_OF_WEEK",
      "kind": "value",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_symbol_info_session_trade_datetime1\"><field name=\"SESSION_INDEX\">0</field><field name=\"TIME_FROM_TO\">1</field></block>"
}
```
