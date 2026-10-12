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
