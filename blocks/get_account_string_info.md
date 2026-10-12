# get_account_string_info

取得帳戶資料(string) 型別

取得帳戶資料(回傳string)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_account_string_info",
  "title": "取得帳戶資料(string) 型別",
  "tooltip": "取得帳戶資料(回傳string)",
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
    }
  ],
  "fields": [
    {
      "name": "ACCOUNT_STRING_INFO",
      "value": "ACCOUNT_NAME",
      "kind": "dropdown",
      "options": [
        {
          "label": "帳戶名稱",
          "value": "ACCOUNT_NAME"
        },
        {
          "label": "伺服器名稱",
          "value": "ACCOUNT_SERVER"
        },
        {
          "label": "貨幣別",
          "value": "ACCOUNT_CURRENCY"
        },
        {
          "label": "卷商名稱",
          "value": "ACCOUNT_COMPANY"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_account_string_info\"><field name=\"ACCOUNT_STRING_INFO\">ACCOUNT_NAME</field></block>"
}
```
