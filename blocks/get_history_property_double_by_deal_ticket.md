# get_history_property_double_by_deal_ticket

(MT5)成交號取歷史交易.成交資料(double) 成交單號 型別

取得歷史交易資料,資料型別小數(double)

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_history_property_double_by_deal_ticket",
  "title": "(MT5)成交號取歷史交易.成交資料(double) 成交單號 型別",
  "tooltip": "取得歷史交易資料,資料型別小數(double)",
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
      "name": "HISTORY_DOUBLE_INFO",
      "value": "DEAL_VOLUME",
      "kind": "dropdown",
      "options": [
        {
          "label": "成交量",
          "value": "DEAL_VOLUME"
        },
        {
          "label": "成交價格",
          "value": "DEAL_PRICE"
        },
        {
          "label": "手續費",
          "value": "DEAL_COMMISSION"
        },
        {
          "label": "利息",
          "value": "DEAL_SWAP"
        },
        {
          "label": "利潤",
          "value": "DEAL_PROFIT"
        },
        {
          "label": "費用",
          "value": "DEAL_FEE"
        },
        {
          "label": "停損價格",
          "value": "DEAL_SL"
        },
        {
          "label": "停利價格",
          "value": "DEAL_TP"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_history_property_double_by_deal_ticket\"><field name=\"HISTORY_DOUBLE_INFO\">DEAL_VOLUME</field></block>"
}
```
