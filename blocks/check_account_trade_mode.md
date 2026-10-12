# check_account_trade_mode

是否 帳號交易模式 為 型別

檢查目前帳戶交易模式

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_account_trade_mode",
  "title": "是否 帳號交易模式 為 型別",
  "tooltip": "檢查目前帳戶交易模式",
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
      "name": "ACCOUNT_TRADE_MODE",
      "value": "ACCOUNT_TRADE_MODE_DEMO",
      "kind": "dropdown",
      "options": [
        {
          "label": "模擬帳號",
          "value": "ACCOUNT_TRADE_MODE_DEMO"
        },
        {
          "label": "競賽帳號",
          "value": "ACCOUNT_TRADE_MODE_CONTEST"
        },
        {
          "label": "真實帳號",
          "value": "ACCOUNT_TRADE_MODE_REAL"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_account_trade_mode\"><field name=\"ACCOUNT_TRADE_MODE\">ACCOUNT_TRADE_MODE_DEMO</field></block>"
}
```
