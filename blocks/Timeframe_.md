# Timeframe_

時間週期

時間週期

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "Timeframe_",
  "title": "時間週期",
  "tooltip": "時間週期",
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
      "name": "TIMEFRAME",
      "value": "PERIOD_CURRENT",
      "kind": "dropdown",
      "options": [
        {
          "label": "目前",
          "value": "PERIOD_CURRENT"
        },
        {
          "label": "1分鐘",
          "value": "PERIOD_M1"
        },
        {
          "label": "2分鐘(MT5)",
          "value": "PERIOD_M2"
        },
        {
          "label": "3分鐘(MT5)",
          "value": "PERIOD_M3"
        },
        {
          "label": "4分鐘(MT5)",
          "value": "PERIOD_M4"
        },
        {
          "label": "5分鐘",
          "value": "PERIOD_M5"
        },
        {
          "label": "6分鐘(MT5)",
          "value": "PERIOD_M6"
        },
        {
          "label": "10分鐘(MT5)",
          "value": "PERIOD_M10"
        },
        {
          "label": "12分鐘(MT5)",
          "value": "PERIOD_M12"
        },
        {
          "label": "15分鐘",
          "value": "PERIOD_M15"
        },
        {
          "label": "20分鐘(MT5)",
          "value": "PERIOD_M20"
        },
        {
          "label": "30分鐘",
          "value": "PERIOD_M30"
        },
        {
          "label": "1小時",
          "value": "PERIOD_H1"
        },
        {
          "label": "2小時(MT5)",
          "value": "PERIOD_H2"
        },
        {
          "label": "3小時(MT5)",
          "value": "PERIOD_H3"
        },
        {
          "label": "4小時",
          "value": "PERIOD_H4"
        },
        {
          "label": "6小時(MT5)",
          "value": "PERIOD_H6"
        },
        {
          "label": "8小時(MT5)",
          "value": "PERIOD_H8"
        },
        {
          "label": "12小時(MT5)",
          "value": "PERIOD_H12"
        },
        {
          "label": "1天",
          "value": "PERIOD_D1"
        },
        {
          "label": "1週",
          "value": "PERIOD_W1"
        },
        {
          "label": "1個月",
          "value": "PERIOD_MN1"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"Timeframe_\"><field name=\"TIMEFRAME\">PERIOD_CURRENT</field></block>"
}
```
