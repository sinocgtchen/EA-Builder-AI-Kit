# property_info

程式屬性說明 版權 連結網站 版本 描述

程式屬性說明(property)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "property_info",
  "title": "程式屬性說明 版權 連結網站 版本 描述",
  "tooltip": "程式屬性說明(property)",
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
      "name": "COPYRIGHT",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "LINK",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "VERSOIN",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "DESCRIPTION",
      "kind": "value",
      "connectionChecks": null
    }
  ],
  "fields": [],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"property_info\"></block>"
}
```

## 程式版本格式

`VERSOIN` 會輸出為 `#property version`，代表 EA／Script 的程式版本。資料包版本與新程式的預設版本統一為 `9.42`；使用者另有指定時採用合法程式版本。只接受一個小數點分隔的兩段數字（各 1 至 3 位）。不要填入 `9.42.1` 或其他三段式版號，以免出現 MT5 Market 版本格式警告。

來源：[MQL5 編譯警告 68](https://www.mql5.com/en/docs/constants/errorswarnings/warningscompile)。
