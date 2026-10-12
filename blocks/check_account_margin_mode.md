# check_account_margin_mode

是否 保證金持倉方式(MT5) 為 型別

檢查保證金持倉方式

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_account_margin_mode",
  "title": "是否 保證金持倉方式(MT5) 為 型別",
  "tooltip": "檢查保證金持倉方式",
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
      "name": "ACCOUNT_MARGIN_MODE",
      "value": "ACCOUNT_MARGIN_MODE_RETAIL_NETTING",
      "kind": "dropdown",
      "options": [
        {
          "label": "單邊持倉(Netting)",
          "value": "ACCOUNT_MARGIN_MODE_RETAIL_NETTING"
        },
        {
          "label": "交易所設定方式",
          "value": "ACCOUNT_MARGIN_MODE_EXCHANGE"
        },
        {
          "label": "對沖方式(Hedging)",
          "value": "ACCOUNT_MARGIN_MODE_RETAIL_HEDGING"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_account_margin_mode\"><field name=\"ACCOUNT_MARGIN_MODE\">ACCOUNT_MARGIN_MODE_RETAIL_NETTING</field></block>"
}
```
