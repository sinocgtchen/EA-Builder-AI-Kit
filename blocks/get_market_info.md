# get_market_info

取得市場資訊 商品 型別

Market Information

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_market_info",
  "title": "取得市場資訊 商品 型別",
  "tooltip": "Market Information",
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
      "name": "TYPE_INFO",
      "value": "MODE_LOW",
      "kind": "dropdown",
      "options": [
        {
          "label": "MODE_LOW",
          "value": "MODE_LOW"
        },
        {
          "label": "MODE_HIGH",
          "value": "MODE_HIGH"
        },
        {
          "label": "MODE_BID",
          "value": "MODE_BID"
        },
        {
          "label": "MODE_ASK",
          "value": "MODE_ASK"
        },
        {
          "label": "MODE_TIME",
          "value": "MODE_TIME"
        },
        {
          "label": "MODE_POINT",
          "value": "MODE_POINT"
        },
        {
          "label": "MODE_DIGITS",
          "value": "MODE_DIGITS"
        },
        {
          "label": "MODE_SPREAD",
          "value": "MODE_SPREAD"
        },
        {
          "label": "MODE_STOPLEVEL",
          "value": "MODE_STOPLEVEL"
        },
        {
          "label": "MODE_LOTSIZE",
          "value": "MODE_LOTSIZE"
        },
        {
          "label": "MODE_TICKVALUE",
          "value": "MODE_TICKVALUE"
        },
        {
          "label": "MODE_TICKSIZE",
          "value": "MODE_TICKSIZE"
        },
        {
          "label": "MODE_SWAPLONG",
          "value": "MODE_SWAPLONG"
        },
        {
          "label": "MODE_SWAPSHORT",
          "value": "MODE_SWAPSHORT"
        },
        {
          "label": "MODE_STARTING",
          "value": "MODE_STARTING"
        },
        {
          "label": "MODE_EXPIRATION",
          "value": "MODE_EXPIRATION"
        },
        {
          "label": "MODE_TRADEALLOWED",
          "value": "MODE_TRADEALLOWED"
        },
        {
          "label": "MODE_MINLOT",
          "value": "MODE_MINLOT"
        },
        {
          "label": "MODE_MAXLOT",
          "value": "MODE_MAXLOT"
        },
        {
          "label": "MODE_LOTSTEP",
          "value": "MODE_LOTSTEP"
        },
        {
          "label": "MODE_PROFITCALCMODE",
          "value": "MODE_PROFITCALCMODE"
        },
        {
          "label": "MODE_MARGINCALCMODE",
          "value": "MODE_MARGINCALCMODE"
        },
        {
          "label": "MODE_MARGININIT",
          "value": "MODE_MARGININIT"
        },
        {
          "label": "MODE_MARGINMAINTENANCE",
          "value": "MODE_MARGINMAINTENANCE"
        },
        {
          "label": "MODE_MARGINHEDGED",
          "value": "MODE_MARGINHEDGED"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_market_info\"><field name=\"TYPE_INFO\">MODE_LOW</field></block>"
}
```
