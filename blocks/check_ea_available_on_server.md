# check_ea_available_on_server

檢查EA是否授權 產品編號 訂單編號 Email 有效年數 有效月數 有效天數

檢查EA是否在有效期內及相關對應網站資訊,須配合MT4EAcheck.dll/MT5EAcheck.dll檔案, 正確回傳EA編號,不正確回傳正數數值

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_ea_available_on_server",
  "title": "檢查EA是否授權 產品編號 訂單編號 Email 有效年數 有效月數 有效天數",
  "tooltip": "檢查EA是否在有效期內及相關對應網站資訊,須配合MT4EAcheck.dll/MT5EAcheck.dll檔案, 正確回傳EA編號,不正確回傳正數數值",
  "offeredInToolbox": {
    "ea": false,
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
      "name": "EA_PRODUCT_ID",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "EA_ORDER_ID",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "EA_EMAIL_ID",
      "kind": "value",
      "connectionChecks": [
        "String"
      ]
    },
    {
      "name": "EA_PERIOD_YEARS",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "EA_PERIOD_MONTHS",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    },
    {
      "name": "EA_PERIOD_DAYS",
      "kind": "value",
      "connectionChecks": [
        "Number"
      ]
    }
  ],
  "fields": [],
  "connections": {
    "output": true,
    "outputChecks": [
      "Number"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_ea_available_on_server\"></block>"
}
```
