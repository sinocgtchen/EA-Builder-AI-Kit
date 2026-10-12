# get_symbol_info_double

取得商品資料(double) 商品 型別

回傳 SymbolInfoDouble()相關資料, 回傳型別為 double

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_symbol_info_double",
  "title": "取得商品資料(double) 商品 型別",
  "tooltip": "回傳 SymbolInfoDouble()相關資料, 回傳型別為 double",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "ENUM_SYMBOL_INFO_DOUBLE",
      "value": "SYMBOL_BID",
      "kind": "dropdown",
      "options": [
        {
          "label": "最佳買價(Bid)",
          "value": "SYMBOL_BID"
        },
        {
          "label": "最佳賣價(Ask)",
          "value": "SYMBOL_ASK"
        },
        {
          "label": "價格最小跳動點值",
          "value": "SYMBOL_POINT"
        },
        {
          "label": "最小變動價格",
          "value": "SYMBOL_TRADE_TICK_SIZE"
        },
        {
          "label": "交易合約大小",
          "value": "SYMBOL_TRADE_CONTRACT_SIZE"
        },
        {
          "label": "一筆訂單中最小成交量",
          "value": "SYMBOL_VOLUME_MIN"
        },
        {
          "label": "一筆訂單中最大成交量",
          "value": "SYMBOL_VOLUME_MAX"
        },
        {
          "label": "交易最小成交量單位數",
          "value": "SYMBOL_VOLUME_STEP"
        },
        {
          "label": "買單利息",
          "value": "SYMBOL_SWAP_LONG"
        },
        {
          "label": "賣單利息",
          "value": "SYMBOL_SWAP_SHORT"
        },
        {
          "label": "原始保證金",
          "value": "SYMBOL_MARGIN_INITIAL"
        },
        {
          "label": "維持保證金",
          "value": "SYMBOL_MARGIN_MAINTENANCE"
        },
        {
          "label": "一個點差的報價價格",
          "value": "SYMBOL_TRADE_TICK_VALUE"
        },
        {
          "label": "一天中最高買價(MT5)",
          "value": "SYMBOL_BIDHIGH"
        },
        {
          "label": "一天中最低買價(MT5)",
          "value": "SYMBOL_BIDLOW"
        },
        {
          "label": "一天中最高賣價(MT5)",
          "value": "SYMBOL_ASKHIGH"
        },
        {
          "label": "一天中最低賣價(MT5)",
          "value": "SYMBOL_ASKLOW"
        },
        {
          "label": "最後訂單價格(MT5)",
          "value": "SYMBOL_LAST"
        },
        {
          "label": "一天中最高價格(MT5)",
          "value": "SYMBOL_LASTHIGH"
        },
        {
          "label": "一天中最低價格(MT5)",
          "value": "SYMBOL_LASTLOW"
        },
        {
          "label": "最後訂單成交量(MT5)",
          "value": "SYMBOL_VOLUME_REAL"
        },
        {
          "label": "當天最大訂單數(MT5)",
          "value": "SYMBOL_VOLUMEHIGH_REAL"
        },
        {
          "label": "當天最小訂單數(MT5)",
          "value": "SYMBOL_VOLUMELOW_REAL"
        },
        {
          "label": "期權預約價格(MT5)",
          "value": "SYMBOL_OPTION_STRIKE"
        },
        {
          "label": "利潤計算最小價位(MT5)",
          "value": "SYMBOL_TRADE_TICK_VALUE_PROFIT"
        },
        {
          "label": "虧損計算最小價位(MT5)",
          "value": "SYMBOL_TRADE_TICK_VALUE_LOSS"
        },
        {
          "label": "可允許最大交易量(MT5)",
          "value": "SYMBOL_VOLUME_LIMIT"
        },
        {
          "label": "當前交易的總交易量(MT5)",
          "value": "SYMBOL_SESSION_VOLUME"
        },
        {
          "label": "當前的總流通量(MT5)",
          "value": "SYMBOL_SESSION_TURNOVER"
        },
        {
          "label": "總持倉利息(MT5)",
          "value": "SYMBOL_SESSION_INTEREST"
        },
        {
          "label": "買入訂單的當前交易量(MT5)",
          "value": "SYMBOL_SESSION_BUY_ORDERS_VOLUME"
        },
        {
          "label": "賣出訂單的當前交易量(MT5)",
          "value": "SYMBOL_SESSION_SELL_ORDERS_VOLUME"
        },
        {
          "label": "當前持倉價格(MT5)",
          "value": "SYMBOL_SESSION_OPEN"
        },
        {
          "label": "當前平倉價格(MT5)",
          "value": "SYMBOL_SESSION_CLOSE"
        },
        {
          "label": "當前加權平均價格(MT5)",
          "value": "SYMBOL_SESSION_AW"
        },
        {
          "label": "當前結算價格(MT5)",
          "value": "SYMBOL_SESSION_PRICE_SETTLEMENT"
        },
        {
          "label": "當前最低價格(MT5)",
          "value": "SYMBOL_SESSION_PRICE_LIMIT_MIN"
        },
        {
          "label": "當前最高價格(MT5)",
          "value": "SYMBOL_SESSION_PRICE_LIMIT_MAX"
        },
        {
          "label": "鎖倉持倉每手的合約大小(MT5)",
          "value": "SYMBOL_MARGIN_HEDGED"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_symbol_info_double\"><field name=\"ENUM_SYMBOL_INFO_DOUBLE\">SYMBOL_BID</field></block>"
}
```
