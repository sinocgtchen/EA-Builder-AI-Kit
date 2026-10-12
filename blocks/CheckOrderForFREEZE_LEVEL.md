# CheckOrderForFREEZE_LEVEL

是否 掛單價格在Ask/Bid凍結區 單號

修改掛單價格前檢查是否掛單價格在市價凍結區(SYMBOL_TRADE_FREEZE_LEVEL).

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "CheckOrderForFREEZE_LEVEL",
  "title": "是否 掛單價格在Ask/Bid凍結區 單號",
  "tooltip": "修改掛單價格前檢查是否掛單價格在市價凍結區(SYMBOL_TRADE_FREEZE_LEVEL).",
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
    },
    {
      "name": "ORDER_TICKET",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"CheckOrderForFREEZE_LEVEL\"></block>"
}
```
