# history_deal_entry_types

(MT5)歷史成交進出類型

取得歷史成交類型

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_deal_entry_types",
  "title": "(MT5)歷史成交進出類型",
  "tooltip": "取得歷史成交類型",
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
      "name": "DEAL_ENTRY_TYPES",
      "value": "DEAL_ENTRY_IN",
      "kind": "dropdown",
      "options": [
        {
          "label": "IN",
          "value": "DEAL_ENTRY_IN"
        },
        {
          "label": "OUT",
          "value": "DEAL_ENTRY_OUT"
        },
        {
          "label": "INOUT",
          "value": "DEAL_ENTRY_INOUT"
        },
        {
          "label": "OUT_BY",
          "value": "DEAL_ENTRY_OUT_BY"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_deal_entry_types\"><field name=\"DEAL_ENTRY_TYPES\">DEAL_ENTRY_IN</field></block>"
}
```
