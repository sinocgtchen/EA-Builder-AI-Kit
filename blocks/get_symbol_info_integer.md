# get_symbol_info_integer

取得商品資料(long/int) 商品 型別

回傳 SymbolInfoInteger()相關資料, 回傳型別為 long

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_symbol_info_integer",
  "title": "取得商品資料(long/int) 商品 型別",
  "tooltip": "回傳 SymbolInfoInteger()相關資料, 回傳型別為 long",
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
      "name": "ENUM_SYMBOL_INFO_INTEGER",
      "value": "SYMBOL_DIGITS",
      "kind": "dropdown",
      "options": [
        {
          "label": "小數點後位數",
          "value": "SYMBOL_DIGITS"
        },
        {
          "label": "點差",
          "value": "SYMBOL_SPREAD"
        },
        {
          "label": "選擇交易商品",
          "value": "SYMBOL_SELECT"
        },
        {
          "label": "最後報價時間",
          "value": "SYMBOL_TIME"
        },
        {
          "label": "下單模式",
          "value": "SYMBOL_TRADE_MODE"
        },
        {
          "label": "止損訂單最小點差",
          "value": "SYMBOL_TRADE_STOPS_LEVEL"
        },
        {
          "label": "凍結交易距離點差",
          "value": "SYMBOL_TRADE_FREEZE_LEVEL"
        },
        {
          "label": "自定義交易商品(MT5)",
          "value": "SYMBOL_CUSTOM"
        },
        {
          "label": "目前交易數量(MT5)",
          "value": "SYMBOL_SESSION_DEALS"
        },
        {
          "label": "目前多單數量(MT5)",
          "value": "SYMBOL_SESSION_BUY_ORDERS"
        },
        {
          "label": "目前空單數量(MT5)",
          "value": "SYMBOL_SESSION_SELL_ORDERS"
        },
        {
          "label": "最後成交量(MT5)",
          "value": "SYMBOL_VOLUME"
        },
        {
          "label": "當天最大成交量(MT5)",
          "value": "SYMBOL_VOLUMEHIGH"
        },
        {
          "label": "當天最小成交量(MT5)",
          "value": "SYMBOL_VOLUMELOW"
        },
        {
          "label": "期限模式(MT5)",
          "value": "SYMBOL_EXPIRATION_MODE"
        },
        {
          "label": "下單執行模式(MT5)",
          "value": "SYMBOL_FILLING_MODE"
        },
        {
          "label": "訂單類型(MT5)",
          "value": "SYMBOL_ORDER_MODE"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_symbol_info_integer\"><field name=\"ENUM_SYMBOL_INFO_INTEGER\">SYMBOL_DIGITS</field></block>"
}
```
