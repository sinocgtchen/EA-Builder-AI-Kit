# messagebox_info

打開訊息視窗 抬頭 訊息內容

顯示訊息到視窗(MessageBox)

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "messagebox_info",
  "title": "打開訊息視窗 抬頭 訊息內容",
  "tooltip": "顯示訊息到視窗(MessageBox)",
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
      "name": "TITLE",
      "kind": "value",
      "connectionChecks": null
    },
    {
      "name": "CONTENT",
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"messagebox_info\"></block>"
}
```
