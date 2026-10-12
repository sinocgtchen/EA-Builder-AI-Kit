# get_symbol_info_string

取得商品資料(string) 商品 型別

回傳SymbolInfoString()相關資料, 回傳型別為 string

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_symbol_info_string",
  "title": "取得商品資料(string) 商品 型別",
  "tooltip": "回傳SymbolInfoString()相關資料, 回傳型別為 string",
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
      "name": "ENUM_SYMBOL_INFO_STRING",
      "value": "SYMBOL_CURRENCY_BASE",
      "kind": "dropdown",
      "options": [
        {
          "label": "商品基礎貨幣",
          "value": "SYMBOL_CURRENCY_BASE"
        },
        {
          "label": "利潤貨幣",
          "value": "SYMBOL_CURRENCY_PROFIT"
        },
        {
          "label": "保證金貨幣別",
          "value": "SYMBOL_CURRENCY_MARGIN"
        },
        {
          "label": "商品描述",
          "value": "SYMBOL_DESCRIPTION"
        },
        {
          "label": "商品樹形通路",
          "value": "SYMBOL_PATH"
        },
        {
          "label": "基礎衍生資產(MT5)",
          "value": "SYMBOL_BASIS"
        },
        {
          "label": "報價的來源(MT5)",
          "value": "SYMBOL_BANK"
        },
        {
          "label": "商品定價公式(MT5)",
          "value": "SYMBOL_FORMULA"
        },
        {
          "label": "ISIN系統中商品名稱(MT5)",
          "value": "SYMBOL_ISIN"
        },
        {
          "label": "交易商品訊息網址(MT5)",
          "value": "SYMBOL_PAGE"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_symbol_info_string\"><field name=\"ENUM_SYMBOL_INFO_STRING\">SYMBOL_CURRENCY_BASE</field></block>"
}
```
