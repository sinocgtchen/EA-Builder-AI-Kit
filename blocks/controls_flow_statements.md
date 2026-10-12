# controls_flow_statements

迴圈

離開當前的 迴圈

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "controls_flow_statements",
  "title": "迴圈",
  "tooltip": "離開當前的 迴圈",
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
    }
  ],
  "fields": [
    {
      "name": "FLOW",
      "value": "BREAK",
      "kind": "dropdown",
      "options": [
        {
          "label": "停止",
          "value": "BREAK"
        },
        {
          "label": "繼續下一個",
          "value": "CONTINUE"
        }
      ]
    }
  ],
  "connections": {
    "output": false,
    "outputChecks": null,
    "previous": true,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"controls_flow_statements\"><field name=\"FLOW\">BREAK</field></block>"
}
```
