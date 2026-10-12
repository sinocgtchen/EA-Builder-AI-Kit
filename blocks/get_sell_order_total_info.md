# get_sell_order_total_info

取得空單部位資料 商品 魔術數字 型別 計算方式

取得空單部位資料

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_sell_order_total_info",
  "title": "取得空單部位資料 商品 魔術數字 型別 計算方式",
  "tooltip": "取得空單部位資料",
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
      "name": "ORDER_INFO_TYPE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "手數",
          "value": "0"
        },
        {
          "label": "魔術數字",
          "value": "1"
        },
        {
          "label": "下單價格",
          "value": "2"
        },
        {
          "label": "停損價格",
          "value": "3"
        },
        {
          "label": "停利價格",
          "value": "4"
        },
        {
          "label": "隔夜利息",
          "value": "5"
        },
        {
          "label": "利潤",
          "value": "6"
        },
        {
          "label": "筆數",
          "value": "7"
        },
        {
          "label": "佣金(MT4)",
          "value": "8"
        }
      ]
    },
    {
      "name": "SUM_AVERAGE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "總和",
          "value": "0"
        },
        {
          "label": "平均值",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_sell_order_total_info\"><field name=\"SYMBOL_CHECKED\">TRUE</field><field name=\"MAGIC_CHECKED\">TRUE</field><field name=\"ORDER_INFO_TYPE\">0</field><field name=\"SUM_AVERAGE\">0</field></block>"
}
```
