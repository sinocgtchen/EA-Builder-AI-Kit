# get_TerminalInfoInteger

取得MT4/MT5平台資訊(int) 型別

取得MT4/MT5平台資訊(int)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "get_TerminalInfoInteger",
  "title": "取得MT4/MT5平台資訊(int) 型別",
  "tooltip": "取得MT4/MT5平台資訊(int)",
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
      "name": "TERMINAL_INFO_INTEGER",
      "value": "TERMINAL_BUILD",
      "kind": "dropdown",
      "options": [
        {
          "label": "版本編號",
          "value": "TERMINAL_BUILD"
        },
        {
          "label": "是否存在MQL5.community帳號",
          "value": "TERMINAL_COMMUNITY_ACCOUNT"
        },
        {
          "label": "是否連接MQL5.community",
          "value": "TERMINAL_COMMUNITY_CONNECTION"
        },
        {
          "label": "是否連接交易伺服器",
          "value": "TERMINAL_CONNECTED"
        },
        {
          "label": "是否允許DLL",
          "value": "TERMINAL_DLLS_ALLOWED"
        },
        {
          "label": "是否允許自動化交易",
          "value": "TERMINAL_TRADE_ALLOWED"
        },
        {
          "label": "是否開啟郵件發送",
          "value": "TERMINAL_EMAIL_ENABLED"
        },
        {
          "label": "是否開啟FTP功能",
          "value": "TERMINAL_FTP_ENABLED"
        },
        {
          "label": "是否允許手機發送通知到MT4/MT5",
          "value": "TERMINAL_NOTIFICATIONS_ENABLED"
        },
        {
          "label": "圖表中最大K棒數",
          "value": "TERMINAL_MAXBARS"
        },
        {
          "label": "是否存在MetaQuotes ID",
          "value": "TERMINAL_MQID"
        },
        {
          "label": "系統CPU核心數量",
          "value": "TERMINAL_CPU_CORES"
        },
        {
          "label": "系統檔案磁碟空間",
          "value": "TERMINAL_DISK_SPACE"
        },
        {
          "label": "實體記憶體空間(MB)",
          "value": "TERMINAL_MEMORY_PHYSICAL"
        },
        {
          "label": "MT4/MT5可用記憶體空間",
          "value": "TERMINAL_MEMORY_TOTAL"
        },
        {
          "label": "剩餘記憶體空間",
          "value": "TERMINAL_MEMORY_AVAILABLE"
        },
        {
          "label": "已使用記憶體空間",
          "value": "TERMINAL_MEMORY_USED"
        },
        {
          "label": "螢幕解析度(DPI)",
          "value": "TERMINAL_SCREEN_DPI"
        },
        {
          "label": "最後一次連接伺服器後經過微秒數",
          "value": "TERMINAL_PING_LAST"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"get_TerminalInfoInteger\"><field name=\"TERMINAL_INFO_INTEGER\">TERMINAL_BUILD</field></block>"
}
```
