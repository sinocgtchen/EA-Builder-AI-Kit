# get_account_integer_info

取得帳戶資料(long/int) 型別

取得帳戶資料(回傳long/int)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_account_integer_info",
  "title": "取得帳戶資料(long/int) 型別",
  "tooltip": "取得帳戶資料(回傳long/int)",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "ACCOUNT_INTEGER_INFO",
      "value": "ACCOUNT_LOGIN",
      "kind": "dropdown",
      "options": [
        {
          "label": "登入帳號",
          "value": "ACCOUNT_LOGIN"
        },
        {
          "label": "槓桿數",
          "value": "ACCOUNT_LEVERAGE"
        },
        {
          "label": "最大允許部位",
          "value": "ACCOUNT_LIMIT_ORDERS"
        },
        {
          "label": "帳戶允許交易",
          "value": "ACCOUNT_TRADE_ALLOWED"
        },
        {
          "label": "帳戶允許EA",
          "value": "ACCOUNT_TRADE_EXPERT"
        },
        {
          "label": "帳戶貨幣最小位數(MT5)",
          "value": "ACCOUNT_CURRENCY_DIGITS"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_account_integer_info\"><field name=\"ACCOUNT_INTEGER_INFO\">ACCOUNT_LOGIN</field></block>"
}
```
