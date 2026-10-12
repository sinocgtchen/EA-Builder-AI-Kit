# check_time_session

是否 目前時間 在此時段 星期一 星期二 星期三 星期四 星期五 星期六 星期日 開始時間 點 分鐘 到 點 分鐘

檢查目前時間是否在每星期區間

支援產生器：mt4, mt5, mt4script, mt5script。

以下 JSON 提供精確名稱、選項及預設 XML；不得以顯示文字取代識別字。

```json
{
  "type": "check_time_session",
  "title": "是否 目前時間 在此時段 星期一 星期二 星期三 星期四 星期五 星期六 星期日 開始時間 點 分鐘 到 點 分鐘",
  "tooltip": "檢查目前時間是否在每星期區間",
  "offeredInToolbox": {
    "ea": false,
    "script": false
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
    },
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
      "name": "",
      "kind": "dummy",
      "connectionChecks": null
    }
  ],
  "fields": [
    {
      "name": "LOCAL_TIME",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "伺服器",
          "value": "0"
        },
        {
          "label": "客戶端",
          "value": "1"
        }
      ]
    },
    {
      "name": "m1",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m2",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m3",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m4",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m5",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m6",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "m7",
      "value": "FALSE",
      "kind": "field",
      "options": null
    },
    {
      "name": "START_HOUR",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
        {
          "label": "1",
          "value": "1"
        },
        {
          "label": "2",
          "value": "2"
        },
        {
          "label": "3",
          "value": "3"
        },
        {
          "label": "4",
          "value": "4"
        },
        {
          "label": "5",
          "value": "5"
        },
        {
          "label": "6",
          "value": "6"
        },
        {
          "label": "7",
          "value": "7"
        },
        {
          "label": "8",
          "value": "8"
        },
        {
          "label": "9",
          "value": "9"
        },
        {
          "label": "10",
          "value": "10"
        },
        {
          "label": "11",
          "value": "11"
        },
        {
          "label": "12",
          "value": "12"
        },
        {
          "label": "13",
          "value": "13"
        },
        {
          "label": "14",
          "value": "14"
        },
        {
          "label": "15",
          "value": "15"
        },
        {
          "label": "16",
          "value": "16"
        },
        {
          "label": "17",
          "value": "17"
        },
        {
          "label": "18",
          "value": "18"
        },
        {
          "label": "19",
          "value": "19"
        },
        {
          "label": "20",
          "value": "20"
        },
        {
          "label": "21",
          "value": "21"
        },
        {
          "label": "22",
          "value": "22"
        },
        {
          "label": "23",
          "value": "23"
        }
      ]
    },
    {
      "name": "START_MINUTE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
        {
          "label": "1",
          "value": "1"
        },
        {
          "label": "2",
          "value": "2"
        },
        {
          "label": "3",
          "value": "3"
        },
        {
          "label": "4",
          "value": "4"
        },
        {
          "label": "5",
          "value": "5"
        },
        {
          "label": "6",
          "value": "6"
        },
        {
          "label": "7",
          "value": "7"
        },
        {
          "label": "8",
          "value": "8"
        },
        {
          "label": "9",
          "value": "9"
        },
        {
          "label": "10",
          "value": "10"
        },
        {
          "label": "11",
          "value": "11"
        },
        {
          "label": "12",
          "value": "12"
        },
        {
          "label": "13",
          "value": "13"
        },
        {
          "label": "14",
          "value": "14"
        },
        {
          "label": "15",
          "value": "15"
        },
        {
          "label": "16",
          "value": "16"
        },
        {
          "label": "17",
          "value": "17"
        },
        {
          "label": "18",
          "value": "18"
        },
        {
          "label": "19",
          "value": "19"
        },
        {
          "label": "20",
          "value": "20"
        },
        {
          "label": "21",
          "value": "21"
        },
        {
          "label": "22",
          "value": "22"
        },
        {
          "label": "23",
          "value": "23"
        },
        {
          "label": "24",
          "value": "24"
        },
        {
          "label": "25",
          "value": "25"
        },
        {
          "label": "26",
          "value": "26"
        },
        {
          "label": "27",
          "value": "27"
        },
        {
          "label": "28",
          "value": "28"
        },
        {
          "label": "29",
          "value": "29"
        },
        {
          "label": "30",
          "value": "30"
        },
        {
          "label": "31",
          "value": "31"
        },
        {
          "label": "32",
          "value": "32"
        },
        {
          "label": "33",
          "value": "33"
        },
        {
          "label": "34",
          "value": "34"
        },
        {
          "label": "35",
          "value": "35"
        },
        {
          "label": "36",
          "value": "36"
        },
        {
          "label": "37",
          "value": "37"
        },
        {
          "label": "38",
          "value": "38"
        },
        {
          "label": "39",
          "value": "39"
        },
        {
          "label": "40",
          "value": "40"
        },
        {
          "label": "41",
          "value": "41"
        },
        {
          "label": "42",
          "value": "42"
        },
        {
          "label": "43",
          "value": "43"
        },
        {
          "label": "44",
          "value": "44"
        },
        {
          "label": "45",
          "value": "45"
        },
        {
          "label": "46",
          "value": "46"
        },
        {
          "label": "47",
          "value": "47"
        },
        {
          "label": "48",
          "value": "48"
        },
        {
          "label": "49",
          "value": "49"
        },
        {
          "label": "50",
          "value": "50"
        },
        {
          "label": "51",
          "value": "51"
        },
        {
          "label": "52",
          "value": "52"
        },
        {
          "label": "53",
          "value": "53"
        },
        {
          "label": "54",
          "value": "54"
        },
        {
          "label": "55",
          "value": "55"
        },
        {
          "label": "56",
          "value": "56"
        },
        {
          "label": "57",
          "value": "57"
        },
        {
          "label": "58",
          "value": "58"
        },
        {
          "label": "59",
          "value": "59"
        }
      ]
    },
    {
      "name": "END_HOUR",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
        {
          "label": "1",
          "value": "1"
        },
        {
          "label": "2",
          "value": "2"
        },
        {
          "label": "3",
          "value": "3"
        },
        {
          "label": "4",
          "value": "4"
        },
        {
          "label": "5",
          "value": "5"
        },
        {
          "label": "6",
          "value": "6"
        },
        {
          "label": "7",
          "value": "7"
        },
        {
          "label": "8",
          "value": "8"
        },
        {
          "label": "9",
          "value": "9"
        },
        {
          "label": "10",
          "value": "10"
        },
        {
          "label": "11",
          "value": "11"
        },
        {
          "label": "12",
          "value": "12"
        },
        {
          "label": "13",
          "value": "13"
        },
        {
          "label": "14",
          "value": "14"
        },
        {
          "label": "15",
          "value": "15"
        },
        {
          "label": "16",
          "value": "16"
        },
        {
          "label": "17",
          "value": "17"
        },
        {
          "label": "18",
          "value": "18"
        },
        {
          "label": "19",
          "value": "19"
        },
        {
          "label": "20",
          "value": "20"
        },
        {
          "label": "21",
          "value": "21"
        },
        {
          "label": "22",
          "value": "22"
        },
        {
          "label": "23",
          "value": "23"
        }
      ]
    },
    {
      "name": "END_MINUTE",
      "value": "0",
      "kind": "dropdown",
      "options": [
        {
          "label": "0",
          "value": "0"
        },
        {
          "label": "1",
          "value": "1"
        },
        {
          "label": "2",
          "value": "2"
        },
        {
          "label": "3",
          "value": "3"
        },
        {
          "label": "4",
          "value": "4"
        },
        {
          "label": "5",
          "value": "5"
        },
        {
          "label": "6",
          "value": "6"
        },
        {
          "label": "7",
          "value": "7"
        },
        {
          "label": "8",
          "value": "8"
        },
        {
          "label": "9",
          "value": "9"
        },
        {
          "label": "10",
          "value": "10"
        },
        {
          "label": "11",
          "value": "11"
        },
        {
          "label": "12",
          "value": "12"
        },
        {
          "label": "13",
          "value": "13"
        },
        {
          "label": "14",
          "value": "14"
        },
        {
          "label": "15",
          "value": "15"
        },
        {
          "label": "16",
          "value": "16"
        },
        {
          "label": "17",
          "value": "17"
        },
        {
          "label": "18",
          "value": "18"
        },
        {
          "label": "19",
          "value": "19"
        },
        {
          "label": "20",
          "value": "20"
        },
        {
          "label": "21",
          "value": "21"
        },
        {
          "label": "22",
          "value": "22"
        },
        {
          "label": "23",
          "value": "23"
        },
        {
          "label": "24",
          "value": "24"
        },
        {
          "label": "25",
          "value": "25"
        },
        {
          "label": "26",
          "value": "26"
        },
        {
          "label": "27",
          "value": "27"
        },
        {
          "label": "28",
          "value": "28"
        },
        {
          "label": "29",
          "value": "29"
        },
        {
          "label": "30",
          "value": "30"
        },
        {
          "label": "31",
          "value": "31"
        },
        {
          "label": "32",
          "value": "32"
        },
        {
          "label": "33",
          "value": "33"
        },
        {
          "label": "34",
          "value": "34"
        },
        {
          "label": "35",
          "value": "35"
        },
        {
          "label": "36",
          "value": "36"
        },
        {
          "label": "37",
          "value": "37"
        },
        {
          "label": "38",
          "value": "38"
        },
        {
          "label": "39",
          "value": "39"
        },
        {
          "label": "40",
          "value": "40"
        },
        {
          "label": "41",
          "value": "41"
        },
        {
          "label": "42",
          "value": "42"
        },
        {
          "label": "43",
          "value": "43"
        },
        {
          "label": "44",
          "value": "44"
        },
        {
          "label": "45",
          "value": "45"
        },
        {
          "label": "46",
          "value": "46"
        },
        {
          "label": "47",
          "value": "47"
        },
        {
          "label": "48",
          "value": "48"
        },
        {
          "label": "49",
          "value": "49"
        },
        {
          "label": "50",
          "value": "50"
        },
        {
          "label": "51",
          "value": "51"
        },
        {
          "label": "52",
          "value": "52"
        },
        {
          "label": "53",
          "value": "53"
        },
        {
          "label": "54",
          "value": "54"
        },
        {
          "label": "55",
          "value": "55"
        },
        {
          "label": "56",
          "value": "56"
        },
        {
          "label": "57",
          "value": "57"
        },
        {
          "label": "58",
          "value": "58"
        },
        {
          "label": "59",
          "value": "59"
        }
      ]
    }
  ],
  "connections": {
    "output": true,
    "outputChecks": [
      "Boolean"
    ],
    "previous": false,
    "next": false
  },
  "defaultXml": "<block xmlns=\"https://developers.google.com/blockly/xml\" type=\"check_time_session\"><field name=\"LOCAL_TIME\">0</field><field name=\"m1\">FALSE</field><field name=\"m2\">FALSE</field><field name=\"m3\">FALSE</field><field name=\"m4\">FALSE</field><field name=\"m5\">FALSE</field><field name=\"m6\">FALSE</field><field name=\"m7\">FALSE</field><field name=\"START_HOUR\">0</field><field name=\"START_MINUTE\">0</field><field name=\"END_HOUR\">0</field><field name=\"END_MINUTE\">0</field></block>"
}
```
