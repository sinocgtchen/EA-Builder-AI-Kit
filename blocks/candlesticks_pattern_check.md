# candlesticks_pattern_check

是否前K棒排列型態 商品 時間週期 型態為

前K棒排列型態如 牛市吞沒型態 熊市吞沒型態

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "candlesticks_pattern_check",
  "title": "是否前K棒排列型態 商品 時間週期 型態為",
  "tooltip": "前K棒排列型態如 牛市吞沒型態 熊市吞沒型態",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "CURRENCY_PAIR",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "TIMEFRAME",
      "kind": "value",
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
      "name": "BAR_PATTERN",
      "value": "1",
      "kind": "dropdown",
      "options": [
        {
          "label": "BullishBar",
          "value": "1"
        },
        {
          "label": "BearishBar",
          "value": "2"
        },
        {
          "label": "lowlowhigh",
          "value": "3"
        },
        {
          "label": "lowhighhigh",
          "value": "4"
        },
        {
          "label": "highhighlow",
          "value": "5"
        },
        {
          "label": "highlowlow",
          "value": "6"
        },
        {
          "label": "highhighhighu",
          "value": "7"
        },
        {
          "label": "lowhighhighu",
          "value": "8"
        },
        {
          "label": "lowlowlowd",
          "value": "9"
        },
        {
          "label": "highlowlowd",
          "value": "10"
        },
        {
          "label": "engulfingbull3",
          "value": "11"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"candlesticks_pattern_check\"><field name=\"BAR_PATTERN\">1</field></block>"
}
```
