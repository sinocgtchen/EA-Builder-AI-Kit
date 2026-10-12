# candlesticks_pattern_shift

是否前K棒排列型態 商品 時間週期 K棒前移 型態為

前K棒排列型態如 牛市吞沒型態 熊市吞沒型態

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "candlesticks_pattern_shift",
  "title": "是否前K棒排列型態 商品 時間週期 K棒前移 型態為",
  "tooltip": "前K棒排列型態如 牛市吞沒型態 熊市吞沒型態",
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
      "name": "KBAR_SHIFT",
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
        },
        {
          "label": "engulfingbear3",
          "value": "12"
        },
        {
          "label": "bullishbar",
          "value": "13"
        },
        {
          "label": "bearlishbar",
          "value": "14"
        },
        {
          "label": "Doji",
          "value": "15"
        },
        {
          "label": "SpinningTop",
          "value": "16"
        },
        {
          "label": "DarkCloudCover",
          "value": "17"
        },
        {
          "label": "PiercingLine",
          "value": "18"
        },
        {
          "label": "Hammer",
          "value": "19"
        },
        {
          "label": "InverseHammer",
          "value": "20"
        },
        {
          "label": "ShootingStar",
          "value": "21"
        },
        {
          "label": "HangingMan",
          "value": "22"
        },
        {
          "label": "MorningStar",
          "value": "23"
        },
        {
          "label": "EveningStar",
          "value": "24"
        },
        {
          "label": "RubbingDojis",
          "value": "25"
        },
        {
          "label": "NoShadowBullish",
          "value": "26"
        },
        {
          "label": "NoShadowBearish",
          "value": "27"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"candlesticks_pattern_shift\"><field name=\"BAR_PATTERN\">1</field></block>"
}
```
