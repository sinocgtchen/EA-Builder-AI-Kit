# indicators_cross_2lines_check

是否兩指標線互相穿越 L1 K棒1指標值 L1 K棒2指標值 L2 K棒1指標值 L2 K棒2指標值 穿越方式

兩指標線互相穿越如 L1向上穿越L2, L1向下穿越L2

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "indicators_cross_2lines_check",
  "title": "是否兩指標線互相穿越 L1 K棒1指標值 L1 K棒2指標值 L2 K棒1指標值 L2 K棒2指標值 穿越方式",
  "tooltip": "兩指標線互相穿越如 L1向上穿越L2, L1向下穿越L2",
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
      "name": "IDR_LINE1_SHIFT_1",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "IDR_LINE1_SHIFT_2",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "IDR_LINE2_SHIFT_1",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "IDR_LINE2_SHIFT_2",
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
      "name": "TYPE_CROSS",
      "value": "1",
      "kind": "dropdown",
      "options": [
        {
          "label": "l1crossupl2",
          "value": "1"
        },
        {
          "label": "l1crossdownl2",
          "value": "2"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"indicators_cross_2lines_check\"><field name=\"TYPE_CROSS\">1</field></block>"
}
```
