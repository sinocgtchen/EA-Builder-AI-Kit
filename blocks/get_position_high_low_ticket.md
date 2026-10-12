# get_position_high_low_ticket

取得最高或最低下單價格單號 商品 魔術數字 下單方式 應用價格

取得帳戶內最高或最低下單價格單號

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_position_high_low_ticket",
  "title": "取得最高或最低下單價格單號 商品 魔術數字 下單方式 應用價格",
  "tooltip": "取得帳戶內最高或最低下單價格單號",
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
    },
    {
      "name": "MAGIC_NUMBER",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "SYMBOL_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "MAGIC_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "TYPE_CHECKED",
      "value": "TRUE",
      "kind": "field",
      "options": null
    },
    {
      "name": "POSITION_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "多單",
          "value": "0"
        },
        {
          "label": "空單",
          "value": "1"
        }
      ]
    },
    {
      "name": "APPLIED_PRICE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "最高價",
          "value": "0"
        },
        {
          "label": "最低價",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_position_high_low_ticket\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"TYPE_CHECKED\">TRUE</field><field name=\"POSITION_TYPE\">0</field><field name=\"APPLIED_PRICE\">0</field></block>"
}
```
