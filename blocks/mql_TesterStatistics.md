# mql_TesterStatistics

優化統計資料 型別

優化統計資料可用於評估優化結果

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "mql_TesterStatistics",
  "title": "優化統計資料 型別",
  "tooltip": "優化統計資料可用於評估優化結果",
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "STATISTICS_TYPE",
      "value": "STAT_INITIAL_DEPOSIT",
      "kind": "dropdown",
      "options": [
        {
          "label": "STAT_INITIAL_DEPOSIT",
          "value": "STAT_INITIAL_DEPOSIT"
        },
        {
          "label": "STAT_WITHDRAWAL",
          "value": "STAT_WITHDRAWAL"
        },
        {
          "label": "STAT_PROFIT",
          "value": "STAT_PROFIT"
        },
        {
          "label": "STAT_GROSS_PROFIT",
          "value": "STAT_GROSS_PROFIT"
        },
        {
          "label": "STAT_MAX_PROFITTRADE",
          "value": "STAT_MAX_PROFITTRADE"
        },
        {
          "label": "STAT_MAX_LOSSTRADE",
          "value": "STAT_MAX_LOSSTRADE"
        },
        {
          "label": "STAT_BALANCEMIN",
          "value": "STAT_BALANCEMIN"
        },
        {
          "label": "STAT_BALANCE_DD",
          "value": "STAT_BALANCE_DD"
        },
        {
          "label": "STAT_BALANCEDD_PERCENT",
          "value": "STAT_BALANCEDD_PERCENT"
        },
        {
          "label": "STAT_BALANCE_DDREL_PERCENT",
          "value": "STAT_BALANCE_DDREL_PERCENT"
        },
        {
          "label": "STAT_BALANCE_DD_RELATIVE",
          "value": "STAT_BALANCE_DD_RELATIVE"
        },
        {
          "label": "STAT_EQUITYMIN",
          "value": "STAT_EQUITYMIN"
        },
        {
          "label": "STAT_EQUITY_DD",
          "value": "STAT_EQUITY_DD"
        },
        {
          "label": "STAT_EQUITYDD_PERCENT",
          "value": "STAT_EQUITYDD_PERCENT"
        },
        {
          "label": "STAT_EQUITY_DDREL_PERCENT",
          "value": "STAT_EQUITY_DDREL_PERCENT"
        },
        {
          "label": "STAT_EQUITY_DD_RELATIVE",
          "value": "STAT_EQUITY_DD_RELATIVE"
        },
        {
          "label": "STAT_EXPECTED_PAYOFF",
          "value": "STAT_EXPECTED_PAYOFF"
        },
        {
          "label": "STAT_PROFIT_FACTOR",
          "value": "STAT_PROFIT_FACTOR"
        },
        {
          "label": "STAT_RECOVERY_FACTOR",
          "value": "STAT_RECOVERY_FACTOR"
        },
        {
          "label": "STAT_SHARPE_RATIO",
          "value": "STAT_SHARPE_RATIO"
        },
        {
          "label": "STAT_MIN_MARGINLEVEL",
          "value": "STAT_MIN_MARGINLEVEL"
        },
        {
          "label": "STAT_CUSTOM_ONTESTER",
          "value": "STAT_CUSTOM_ONTESTER"
        },
        {
          "label": "STAT_DEALS",
          "value": "STAT_DEALS"
        },
        {
          "label": "STAT_TRADES",
          "value": "STAT_TRADES"
        },
        {
          "label": "STAT_PROFIT_TRADES",
          "value": "STAT_PROFIT_TRADES"
        },
        {
          "label": "STAT_LOSS_TRADES",
          "value": "STAT_LOSS_TRADES"
        },
        {
          "label": "STAT_SHORT_TRADES",
          "value": "STAT_SHORT_TRADES"
        },
        {
          "label": "STAT_LONG_TRADES",
          "value": "STAT_LONG_TRADES"
        },
        {
          "label": "STAT_PROFIT_SHORTTRADES",
          "value": "STAT_PROFIT_SHORTTRADES"
        },
        {
          "label": "STAT_PROFIT_LONGTRADES",
          "value": "STAT_PROFIT_LONGTRADES"
        },
        {
          "label": "STAT_PROFITTRADES_AVGCON",
          "value": "STAT_PROFITTRADES_AVGCON"
        },
        {
          "label": "STAT_LOSSTRADES_AVGCON",
          "value": "STAT_LOSSTRADES_AVGCON"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"mql_TesterStatistics\"><field name=\"STATISTICS_TYPE\">STAT_INITIAL_DEPOSIT</field></block>"
}
```
