# chart_color_set

設定目前圖表各項顏色 顏色

設定目前圖表各項顏色

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "chart_color_set",
  "title": "設定目前圖表各項顏色 顏色",
  "tooltip": "設定目前圖表各項顏色",
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
    },
    {
      "name": "CHART_COLOR",
      "kind": "value",
      "connectionChecks": [
        "Colour"
      ]
    }
  ],
  "fields": [
    {
      "name": "COLOR_CODE",
      "value": "CHART_COLOR_BACKGROUND",
      "kind": "dropdown",
      "options": [
        {
          "label": "背景顏色",
          "value": "CHART_COLOR_BACKGROUND"
        },
        {
          "label": "前景顏色",
          "value": "CHART_COLOR_FOREGROUND"
        },
        {
          "label": "網格顏色",
          "value": "CHART_COLOR_GRID"
        },
        {
          "label": "下單顏色",
          "value": "CHART_COLOR_VOLUME"
        },
        {
          "label": "牛K棒引線顏色",
          "value": "CHART_COLOR_CHART_UP"
        },
        {
          "label": "熊K棒引線顏色",
          "value": "CHART_COLOR_CHART_DOWN"
        },
        {
          "label": "牛K棒顏色",
          "value": "CHART_COLOR_CANDLE_BULL"
        },
        {
          "label": "熊K棒顏色",
          "value": "CHART_COLOR_CANDLE_BEAR"
        },
        {
          "label": "Bid價格顏色",
          "value": "CHART_COLOR_BID"
        },
        {
          "label": "Ask價格顏色",
          "value": "CHART_COLOR_ASK"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"chart_color_set\"><field name=\"COLOR_CODE\">CHART_COLOR_BACKGROUND</field></block>"
}
```
