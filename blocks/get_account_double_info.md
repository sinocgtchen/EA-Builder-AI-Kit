# get_account_double_info

取得帳戶資料(double) 型別

取得帳戶資料(回傳double)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_account_double_info",
  "title": "取得帳戶資料(double) 型別",
  "tooltip": "取得帳戶資料(回傳double)",
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
      "name": "ACCOUNT_DOUBLE_INFO",
      "value": "ACCOUNT_BALANCE",
      "kind": "dropdown",
      "options": [
        {
          "label": "餘額",
          "value": "ACCOUNT_BALANCE"
        },
        {
          "label": "虧損",
          "value": "ACCOUNT_CREDIT"
        },
        {
          "label": "利潤",
          "value": "ACCOUNT_PROFIT"
        },
        {
          "label": "淨值",
          "value": "ACCOUNT_EQUITY"
        },
        {
          "label": "保證金",
          "value": "ACCOUNT_MARGIN"
        },
        {
          "label": "可用保證金",
          "value": "ACCOUNT_MARGIN_FREE"
        },
        {
          "label": "保證金百分比",
          "value": "ACCOUNT_MARGIN_LEVEL"
        },
        {
          "label": "保證金調用百分比",
          "value": "ACCOUNT_MARGIN_SO_CALL"
        },
        {
          "label": "保證金停用百分比",
          "value": "ACCOUNT_MARGIN_SO_SO"
        },
        {
          "label": "初始保證金",
          "value": "ACCOUNT_MARGIN_INITIAL"
        },
        {
          "label": "維持保證金",
          "value": "ACCOUNT_MARGIN_MAINTENANCE"
        },
        {
          "label": "活動資本",
          "value": "ACCOUNT_ASSETS"
        },
        {
          "label": "流動負債",
          "value": "ACCOUNT_LIABILITIES"
        },
        {
          "label": "鎖定手續費金額",
          "value": "ACCOUNT_COMMISSION_BLOCKED"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_account_double_info\"><field name=\"ACCOUNT_DOUBLE_INFO\">ACCOUNT_BALANCE</field></block>"
}
```
