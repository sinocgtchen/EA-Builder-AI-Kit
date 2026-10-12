# get_order_info_string

用單號取得單筆下單資料(string) 單號 型別

用單號取得單筆下單資料(回傳string)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_order_info_string",
  "title": "用單號取得單筆下單資料(string) 單號 型別",
  "tooltip": "用單號取得單筆下單資料(回傳string)",
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
      "name": "ORDER_TICKET",
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
      "name": "ORDER_INFO",
      "value": "Symbol",
      "kind": "dropdown",
      "options": [
        {
          "label": "商品",
          "value": "Symbol"
        },
        {
          "label": "註解",
          "value": "Comment"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "String"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_order_info_string\"><field name=\"ORDER_INFO\">Symbol</field></block>"
}
```
