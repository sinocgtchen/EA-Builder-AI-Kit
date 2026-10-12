# history_order_state

(MT5)歷史訂單狀態

歷史訂單狀態

支援產生器：mt4, mt5。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "history_order_state",
  "title": "(MT5)歷史訂單狀態",
  "tooltip": "歷史訂單狀態",
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
    }
  ],
  "fields": [
    {
      "name": "ORDER_STATE",
      "value": "ORDER_STATE_STARTED",
      "kind": "dropdown",
      "options": [
        {
          "label": "開始",
          "value": "ORDER_STATE_STARTED"
        },
        {
          "label": "已提交",
          "value": "ORDER_STATE_PLACED"
        },
        {
          "label": "已取消",
          "value": "ORDER_STATE_CANCELED"
        },
        {
          "label": "部分執行",
          "value": "ORDER_STATE_PARTIAL"
        },
        {
          "label": "完全執行",
          "value": "ORDER_STATE_FILLED"
        },
        {
          "label": "被拒絕",
          "value": "ORDER_STATE_REJECTED"
        },
        {
          "label": "已過期",
          "value": "ORDER_STATE_EXPIRED"
        },
        {
          "label": "添加請求",
          "value": "ORDER_STATE_REQUEST_ADD"
        },
        {
          "label": "修改請求",
          "value": "ORDER_STATE_REQUEST_MODIFY"
        },
        {
          "label": "取消請求",
          "value": "ORDER_STATE_REQUEST_CANCEL"
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
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"history_order_state\"><field name=\"ORDER_STATE\">ORDER_STATE_STARTED</field></block>"
}
```
