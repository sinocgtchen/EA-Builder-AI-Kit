# get_percentage_price_move_back

最高/最低價格縮回百分比 頂點價格 基準價格 以買賣價計算

從最高/最低價格縮回到基準價格的百分比

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_percentage_price_move_back",
  "title": "最高/最低價格縮回百分比 頂點價格 基準價格 以買賣價計算",
  "tooltip": "從最高/最低價格縮回到基準價格的百分比",
  "offeredInToolbox": {
    "ea": true,
    "script": false
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
      "name": "PEAK_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "BASE_PRICE",
      "kind": "value",
      "connectionChecks": [
        "Number"
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
      "name": "ASK_BID",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "商品賣出價(Ask)",
          "value": "0"
        },
        {
          "label": "商品買入價(Bid)",
          "value": "1"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_percentage_price_move_back\"><field name=\"ASK_BID\">0</field></block>"
}
```
