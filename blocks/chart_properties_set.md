# chart_properties_set

設定目前圖表屬性

設定目前圖表屬性

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "chart_properties_set",
  "title": "設定目前圖表屬性",
  "tooltip": "設定目前圖表屬性",
  "offeredInToolbox": {
    "ea": true,
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "CHART_MODE",
      "value": "CHART_SHOW_GRID",
      "kind": "dropdown",
      "options": [
        {
          "label": "顯示網格",
          "value": "CHART_SHOW_GRID"
        },
        {
          "label": "隱藏網格",
          "value": "CHART_NOSHOW_GRID"
        },
        {
          "label": "柱狀圖",
          "value": "CHART_MODE_BARS"
        },
        {
          "label": "蠟燭圖",
          "value": "CHART_MODE_CANDLES"
        },
        {
          "label": "線條圖",
          "value": "CHART_MODE_LINE"
        },
        {
          "label": "顯示成交量",
          "value": "CHART_SHOW_VOLUMES"
        },
        {
          "label": "右邊縮排",
          "value": "CHART_SHIFT"
        },
        {
          "label": "自動滾動",
          "value": "CHART_AUTOSCROLL"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": true
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"chart_properties_set\"><field name=\"CHART_MODE\">CHART_SHOW_GRID</field></block>"
}
```
