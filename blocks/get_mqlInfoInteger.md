# get_mqlInfoInteger

取得MQL程式資料(int) 型別

取得MQL程式資料(int)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_mqlInfoInteger",
  "title": "取得MQL程式資料(int) 型別",
  "tooltip": "取得MQL程式資料(int)",
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
      "name": "MQL_INFO_INTEGER",
      "value": "MQL_DLLS_ALLOWED",
      "kind": "dropdown",
      "options": [
        {
          "label": "允許使用DLL",
          "value": "MQL_DLLS_ALLOWED"
        },
        {
          "label": "允許交易",
          "value": "MQL_TRADE_ALLOWED"
        },
        {
          "label": "允許更改訊號",
          "value": "MQL_SIGNALS_ALLOWED"
        },
        {
          "label": "除錯模式(DEBUG)",
          "value": "MQL_DEBUG"
        },
        {
          "label": "分析模式",
          "value": "MQL_PROFILER"
        },
        {
          "label": "回測模式",
          "value": "MQL_TESTER"
        },
        {
          "label": "最佳化模式",
          "value": "MQL_OPTIMIZATION"
        },
        {
          "label": "復盤/視覺模式",
          "value": "MQL_VISUAL_MODE"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_mqlInfoInteger\"><field name=\"MQL_INFO_INTEGER\">MQL_DLLS_ALLOWED</field></block>"
}
```
