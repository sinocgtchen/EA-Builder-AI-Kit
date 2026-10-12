# history_deal_reason

(MT5)歷史成交原因

歷史交易執行的原因

支援產生器：mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_deal_reason",
  "title": "(MT5)歷史成交原因",
  "tooltip": "歷史交易執行的原因",
  "offeredInToolbox": {
    "ea": true,
    "script": false
  },
  "generatorAvailable": {
    "mt4": false,
    "mt5": true,
    "mt4script": false,
    "mt5script": false
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
      "name": "DEAL_REASON",
      "value": "DEAL_REASON_CLIENT",
      "kind": "dropdown",
      "options": [
        {
          "label": "客戶端交易",
          "value": "DEAL_REASON_CLIENT"
        },
        {
          "label": "移動端交易",
          "value": "DEAL_REASON_MOBILE"
        },
        {
          "label": "網頁端交易",
          "value": "DEAL_REASON_WEB"
        },
        {
          "label": "自動交易(EA)",
          "value": "DEAL_REASON_EXPERT"
        },
        {
          "label": "止損交易",
          "value": "DEAL_REASON_SL"
        },
        {
          "label": "停利交易",
          "value": "DEAL_REASON_TP"
        },
        {
          "label": "資金不足交易",
          "value": "DEAL_REASON_SO"
        },
        {
          "label": "轉倉",
          "value": "DEAL_REASON_ROLLOVER"
        },
        {
          "label": "變動保證金",
          "value": "DEAL_REASON_VMARGIN"
        },
        {
          "label": "股票拆分",
          "value": "DEAL_REASON_SPLIT"
        },
        {
          "label": "公司執行",
          "value": "DEAL_REASON_CORPORATE_ACTION"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_deal_reason\"><field name=\"DEAL_REASON\">DEAL_REASON_CLIENT</field></block>"
}
```
