# history_deal_types

(MT5)歷史成交方式

歷史成交方式

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_deal_types",
  "title": "(MT5)歷史成交方式",
  "tooltip": "歷史成交方式",
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
    }
  ],
  "fields": [
    {
      "name": "DEAL_TYPES",
      "value": "DEAL_TYPE_BUY",
      "kind": "dropdown",
      "options": [
        {
          "label": "多單",
          "value": "DEAL_TYPE_BUY"
        },
        {
          "label": "空單",
          "value": "DEAL_TYPE_SELL"
        },
        {
          "label": "餘額",
          "value": "DEAL_TYPE_BALANCE"
        },
        {
          "label": "信貸",
          "value": "DEAL_TYPE_CREDIT"
        },
        {
          "label": "額外收費",
          "value": "DEAL_TYPE_CHARGE"
        },
        {
          "label": "修正",
          "value": "DEAL_TYPE_CORRECTION"
        },
        {
          "label": "獎金",
          "value": "DEAL_TYPE_BONUS"
        },
        {
          "label": "額外手續費",
          "value": "DEAL_TYPE_COMMISSION"
        },
        {
          "label": "日手續費",
          "value": "DEAL_TYPE_COMMISSION_DAILY"
        },
        {
          "label": "月手續費",
          "value": "DEAL_TYPE_COMMISSION_MONTHLY"
        },
        {
          "label": "日代理手續費",
          "value": "DEAL_TYPE_COMMISSION_AGENT_DAILY"
        },
        {
          "label": "月代理手續費",
          "value": "DEAL_TYPE_COMMISSION_AGENT_MONTHLY"
        },
        {
          "label": "利率",
          "value": "DEAL_TYPE_INTEREST"
        },
        {
          "label": "取消的買入交易",
          "value": "DEAL_TYPE_BUY_CANCELED"
        },
        {
          "label": "取消的賣出交易",
          "value": "DEAL_TYPE_SELL_CANCELED"
        },
        {
          "label": "紅利操作",
          "value": "DEAL_DIVIDEND"
        },
        {
          "label": "額外紅利",
          "value": "DEAL_DIVIDEND_FRANKED"
        },
        {
          "label": "稅費",
          "value": "DEAL_TAX"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_deal_types\"><field name=\"DEAL_TYPES\">DEAL_TYPE_BUY</field></block>"
}
```
