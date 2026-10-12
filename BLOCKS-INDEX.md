# 積木規格索引

請只選用此索引列出的積木，並讀取個別規格中的精確欄位及輸入名稱。支援表示有產生器函式，仍需編譯驗證。

| 積木類型 | 名稱 | 產生器支援 | 規格 |
| --- | --- | --- | --- |
| `CheckOrderForFREEZE_LEVEL` | 是否 掛單價格在Ask/Bid凍結區 單號 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/CheckOrderForFREEZE_LEVEL.md) |
| `CheckPositionForFREEZE_LEVEL` | 是否 停損停利價格在Ask/Bid禁止修改區 單號 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/CheckPositionForFREEZE_LEVEL.md) |
| `DynamicLot_Size` | 依風險百分比取得手數 偶數輸出 商品 風險依據 百分比 停損(點差) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/DynamicLot_Size.md) |
| `Send_messages_mobile` | 發送訊息到手機MT4/MT5 訊息 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/Send_messages_mobile.md) |
| `Server_is_Connected` | 檢查是否與伺服器連線中 | mt4, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/Server_is_Connected.md) |
| `Symbol_` | 目前商品 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/Symbol_.md) |
| `TesterDisplayIndicators` | 回測時顯示指標 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/TesterDisplayIndicators.md) |
| `TesterHideIndicators` | 回測時隱藏指標 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/TesterHideIndicators.md) |
| `Timeframe_` | 時間週期 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/Timeframe_.md) |
| `alert_info` | 輸出警告訊息 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/alert_info.md) |
| `alert_playsound` | 播放聲音檔案 檔案名稱 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/alert_playsound.md) |
| `base_map` | 對應  數值 到 [ - ] | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/base_map.md) |
| `block_custom_codes_get` | 自製積木  程式碼 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/block_custom_codes_get.md) |
| `block_custom_codes_set` | 自製積木  程式碼 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/block_custom_codes_set.md) |
| `buy_order_Ret` | 多單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_Ret.md) |
| `buy_order_close` | 多單平倉 商品 魔術數字 手數 最大滑點 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_close.md) |
| `buy_order_close_all` | 全部多單平倉 商品 魔術數字 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_close_all.md) |
| `buy_order_noRet` | 多單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_noRet.md) |
| `buy_order_send_pip_price` | 多單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_send_pip_price.md) |
| `buy_order_send_pip_price_noRet` | 多單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_send_pip_price_noRet.md) |
| `candlesticks_cross_line_check` | 是否價格穿越指標 商品 時間週期 穿越方式 指標數值 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/candlesticks_cross_line_check.md) |
| `candlesticks_pattern_check` | 是否前K棒排列型態 商品 時間週期 型態為 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/candlesticks_pattern_check.md) |
| `candlesticks_pattern_shift` | 是否前K棒排列型態 商品 時間週期 K棒前移 型態為 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/candlesticks_pattern_shift.md) |
| `chart_close` | 關閉指定商品圖表 圖表編號 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/chart_close.md) |
| `chart_color_set` | 設定目前圖表各項顏色 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/chart_color_set.md) |
| `chart_open` | 開啟指定商品圖表 商品 時間週期 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/chart_open.md) |
| `chart_properties_set` | 設定目前圖表屬性 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/chart_properties_set.md) |
| `chart_set_symbol_period` | 在目前圖表更改商品名稱及週期 商品 時間週期 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/chart_set_symbol_period.md) |
| `check_SL_TP_for_trade` | 是否 停損停利符合下單最小距離 商品 停損價格 停利價格 下單方式 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_SL_TP_for_trade.md) |
| `check_account_margin_mode` | 是否 保證金持倉方式(MT5) 為 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_account_margin_mode.md) |
| `check_account_trade_mode` | 是否 帳號交易模式 為 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_account_trade_mode.md) |
| `check_datetime_session` | 是否 目前時間 在此時段 開始日期 到 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_datetime_session.md) |
| `check_ea_available_on_server` | 檢查EA是否授權 產品編號 訂單編號 Email 有效年數 有效月數 有效天數 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_ea_available_on_server.md) |
| `check_file_ea_available_on_server` | 雲端檔案內EA是否授權 KEY(授權碼) 檔案(表格)名稱 EA編號(ID) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_file_ea_available_on_server.md) |
| `check_file_ea_expiration_on_server` | 取得EA有效期限 KEY(授權碼) 檔案(表格)名稱 EA編號(ID) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_file_ea_expiration_on_server.md) |
| `check_file_ea_version_on_server` | 取得EA版本編號 KEY(授權碼) 檔案(表格)名稱 EA編號(ID) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_file_ea_version_on_server.md) |
| `check_history_last_trade_profit` | 是否 (MT4)最後一筆歷史交易 商品 魔術數字 為 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_history_last_trade_profit.md) |
| `check_history_order_type_by_ticket` | 是否 歷史交易單號 為 下單方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_history_order_type_by_ticket.md) |
| `check_money_for_trade` | 是否 保證金足夠交易 商品 手數 下單方式 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_money_for_trade.md) |
| `check_new_bar` | 是否為新K棒 商品 時間週期 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_new_bar.md) |
| `check_order_type_by_ticket` | 是否 下單 單號 為 下單方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_order_type_by_ticket.md) |
| `check_pending_order_type_by_ticket` | 是否 掛單 單號 為 掛單方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_pending_order_type_by_ticket.md) |
| `check_time_session` | 是否 目前時間 在此時段 星期一 星期二 星期三 星期四 星期五 星期六 星期日 開始時間 點 分鐘 到 點 分鐘 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_time_session.md) |
| `check_volume_for_trade` | 是否 有效下單手數大小 手數 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_volume_for_trade.md) |
| `check_weektime_session` | 是否 目前時間 在此時段 星期一 星期二 星期三 星期四 星期五 星期六 星期日 開始時間 點 分鐘 到 點 分鐘 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_weektime_session.md) |
| `checkbox_object_get_503` | 取得複選框狀態 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/checkbox_object_get_503.md) |
| `checkbox_object_get_917` | 取得複選框狀態 編號 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/checkbox_object_get_917.md) |
| `color_to_string` | 顏色(color) 轉換成字串 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/color_to_string.md) |
| `colour_blend` | 混合 顏色 1 顏色 2 比例 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/colour_blend.md) |
| `colour_picker` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/colour_picker.md) |
| `colour_random` | 隨機顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/colour_random.md) |
| `colour_rgb` | 顏色 紅 綠 藍 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/colour_rgb.md) |
| `combo1_checkbox_edit_get_503` | (組合1)取得狀態及資料 編號 物件 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/combo1_checkbox_edit_get_503.md) |
| `combo1_checkbox_get` | (組合1)取得 複選框狀態(真/否) 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/combo1_checkbox_get.md) |
| `combo1_edit_get` | (組合1)取得 編輯欄位資料 編號 回傳 型別 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/combo1_edit_get.md) |
| `combo2_edit_get` | (組合2)取得 編輯欄位資料 編號 回傳 型別 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/combo2_edit_get.md) |
| `comment_info` | 輸出註釋訊息在圖表左上角 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/comment_info.md) |
| `controls_flow_statements` | 迴圈 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/controls_flow_statements.md) |
| `controls_for` | 使用 從範圍 到 每隔 執行 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/controls_for.md) |
| `controls_if` | 如果 執行 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/controls_if.md) |
| `controls_repeat_ext` | 重複 次 執行 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/controls_repeat_ext.md) |
| `controls_whileUntil` | 重複 執行 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/controls_whileUntil.md) |
| `conversion_tobyte` | 轉換到位元組 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/conversion_tobyte.md) |
| `conversion_tochar` | 轉換到字元 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/conversion_tochar.md) |
| `conversion_tofloat` | 轉換到小數 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/conversion_tofloat.md) |
| `conversion_toint` | 轉換到整數 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/conversion_toint.md) |
| `convert_to_datetime` | 指定時間 年 月 日 時 分 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/convert_to_datetime.md) |
| `datetime_to_string` | 指定時間表示成文字字串 年 月 日 時 分 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/datetime_to_string.md) |
| `delay` | 延遲毫秒 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delay.md) |
| `delayMicroseconds` | 延遲微秒 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delayMicroseconds.md) |
| `delayMicroseconds_custom` | 延遲微秒 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delayMicroseconds_custom.md) |
| `delay_custom` | 延遲毫秒 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delay_custom.md) |
| `delete_all_trades` | 刪除所有已下單及掛單 商品 魔術數字 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delete_all_trades.md) |
| `delete_pending_orders_all` | 依掛單方式刪除所有掛單 商品 魔術數字 掛單方式 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delete_pending_orders_all.md) |
| `delete_pending_orders_by_ticket` | 依單號刪除掛單 單號 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/delete_pending_orders_by_ticket.md) |
| `edit_object_data_get` | 取得編輯欄位資料 編號 回傳 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/edit_object_data_get.md) |
| `edit_object_data_get_503` | 取得編輯欄位資料 編號 回傳 型別 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/edit_object_data_get_503.md) |
| `edit_object_data_get_917` | 取得編輯欄位資料 編號 回傳 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/edit_object_data_get_917.md) |
| `enum_create` | 建立列舉式資料(enum) 變數名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/enum_create.md) |
| `enum_to_string` | 列舉式資料(enum) 轉換成字串 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/enum_to_string.md) |
| `expert_remove` | EA停止運行 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/expert_remove.md) |
| `experts_indicator_val` | 指標 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/experts_indicator_val.md) |
| `file_chart_apply_template` | 在圖表中開啟指定模板(template) 圖表編號 模板名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_chart_apply_template.md) |
| `file_chart_save_template` | 儲存圖表中的設置到指定模板(template) 圖表編號 模板名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_chart_save_template.md) |
| `file_check_csvfileread_ending` | 是否檔案資料讀取到最後 檔案代碼 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_check_csvfileread_ending.md) |
| `file_check_file_exist` | 是否檔案存在 檔案名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_check_file_exist.md) |
| `file_csvclosefile` | 關閉檔案 檔案代碼 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_csvclosefile.md) |
| `file_csvfileread_general` | 讀取檔案資料 檔案代碼 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_csvfileread_general.md) |
| `file_csvfileread_string` | 讀取檔案資料 檔案代碼 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_csvfileread_string.md) |
| `file_csvfilewrite` | 寫入資料到檔案 檔案代碼 資料 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_csvfilewrite.md) |
| `file_csvopenfile` | 開啟檔案(回傳檔案代碼) 檔案名稱 分隔符號 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_csvopenfile.md) |
| `file_deletefile` | 刪除檔案 檔案名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_deletefile.md) |
| `file_fileseek` | 設定讀寫檔案位置(回傳真/否) 檔案代碼 位移 讀寫位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/file_fileseek.md) |
| `get_TerminalInfoInteger` | 取得MT4/MT5平台資訊(int) 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_TerminalInfoInteger.md) |
| `get_TimeDaylightSavings` | 是否為日光節約時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_TimeDaylightSavings.md) |
| `get_TimeGMT` | 取得相對於目前電腦的GMT時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_TimeGMT.md) |
| `get_account_double_info` | 取得帳戶資料(double) 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_account_double_info.md) |
| `get_account_integer_info` | 取得帳戶資料(long/int) 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_account_integer_info.md) |
| `get_account_margin_mode` | 保證金持倉方式(MT5) 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_account_margin_mode.md) |
| `get_account_string_info` | 取得帳戶資料(string) 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_account_string_info.md) |
| `get_applied_price` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_applied_price.md) |
| `get_bar_price` | 取得K棒價格 商品 時間週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_bar_price.md) |
| `get_bar_size` | 取得K棒長度 商品 時間週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_bar_size.md) |
| `get_bar_tick_volume` | 回傳K棒的報價量 商品 時間週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_bar_tick_volume.md) |
| `get_buy_order_total` | 取得多單部位資料 商品 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_buy_order_total.md) |
| `get_buy_order_total_counts` | 多單 目前筆數 商品 魔術數字 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_buy_order_total_counts.md) |
| `get_buy_order_total_info` | 取得多單部位資料 商品 魔術數字 型別 計算方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_buy_order_total_info.md) |
| `get_comments_by_ticket` | 依單號取得註解 單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_comments_by_ticket.md) |
| `get_current_datetime` | 取得 目前時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_current_datetime.md) |
| `get_current_timeframe` | 取得目前圖表時間週期 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_current_timeframe.md) |
| `get_datetime` | 取得 目前時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_datetime.md) |
| `get_double_to_string` | 轉換型別 小數(double) 到 字串(string) 小數點後的位數 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_double_to_string.md) |
| `get_field_days_hours_mins` | 有效時間 日 小時 分鐘 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_field_days_hours_mins.md) |
| `get_history_deal_ticket_by_position` | (MT5)取得歷史交易.成交單號 最近 第 筆 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_deal_ticket_by_position.md) |
| `get_history_last_trade_property_double` | 取得 (MT4)最後一筆歷史交易 (double) 商品 魔術數字 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_last_trade_property_double.md) |
| `get_history_last_trade_property_integer` | 取得 (MT4)最後一筆歷史交易 (long) 商品 魔術數字 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_last_trade_property_integer.md) |
| `get_history_order_ticket_by_position` | (MT5)取得歷史交易.訂單單號 最近 第 筆 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_order_ticket_by_position.md) |
| `get_history_position_ticket_by_position` | (MT5)取得歷史交易.持倉單號 最近 第 筆 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_position_ticket_by_position.md) |
| `get_history_property_datetime_by_deal_ticket` | (MT5)成交號取歷史交易.成交資料(long/int) 成交單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_datetime_by_deal_ticket.md) |
| `get_history_property_datetime_by_order_ticket` | (MT5)訂單號取歷史交易.訂單資料(long/int) 訂單單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_datetime_by_order_ticket.md) |
| `get_history_property_datetime_by_position_ticket` | (MT5)持倉號取歷史交易.持倉資料(long/int) 持倉單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_datetime_by_position_ticket.md) |
| `get_history_property_datetime_by_ticket` | (MT4)取得歷史交易資料(long/int) 歷史交易單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_datetime_by_ticket.md) |
| `get_history_property_double_by_deal_ticket` | (MT5)成交號取歷史交易.成交資料(double) 成交單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_double_by_deal_ticket.md) |
| `get_history_property_double_by_order_ticket` | (MT5)訂單號取歷史交易.訂單資料(double) 訂單單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_double_by_order_ticket.md) |
| `get_history_property_double_by_position_ticket` | (MT5)持倉號取歷史交易.持倉資料(double) 持倉單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_double_by_position_ticket.md) |
| `get_history_property_double_by_ticket` | (MT4)取得歷史交易資料(double) 歷史交易單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_double_by_ticket.md) |
| `get_history_property_string_by_deal_ticket` | (MT5)成交號取歷史交易.成交資料(string) 成交單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_string_by_deal_ticket.md) |
| `get_history_property_string_by_order_ticket` | (MT5)訂單號取歷史交易.訂單資料(string) 訂單單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_string_by_order_ticket.md) |
| `get_history_property_string_by_position_ticket` | (MT5)持倉號取歷史交易.持倉資料(string) 持倉單號 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_string_by_position_ticket.md) |
| `get_history_property_string_by_ticket` | (MT4)取得歷史交易資料(string) 歷史交易單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_property_string_by_ticket.md) |
| `get_history_ticket_by_position` | (MT4)利用出場順序取得 歷史交易單號 最近 第 筆 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_ticket_by_position.md) |
| `get_history_trades_total` | (MT4)取得歷史交易筆數 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_trades_total.md) |
| `get_history_trades_total_deal` | (MT5)取得歷史交易.成交筆數 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_trades_total_deal.md) |
| `get_history_trades_total_order` | (MT5)取得歷史交易.訂單筆數 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_trades_total_order.md) |
| `get_history_trades_total_position` | (MT5)取得歷史交易.持倉筆數 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_history_trades_total_position.md) |
| `get_ima_methods` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_ima_methods.md) |
| `get_kbar_amount` | 取得圖表中K棒數 商品 時間週期 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbar_amount.md) |
| `get_kbar_datetime` | 取得K棒時間 K棒前移 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbar_datetime.md) |
| `get_kbar_datetime_format` | 取得K棒時間 商品 時間週期 K棒前移 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbar_datetime_format.md) |
| `get_kbars_highest_lowest_index` | 取得 數值索引位置 商品 時間週期 型別 K棒前移 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbars_highest_lowest_index.md) |
| `get_kbars_highest_lowest_price` | 取得K棒 商品 時間週期 型別 K棒前移 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbars_highest_lowest_price.md) |
| `get_kbars_index_by_datetime` | 用時間取得K棒前移(索引)位置 商品 時間週期 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbars_index_by_datetime.md) |
| `get_kbars_order_time_by_ticket` | 用單號取得下單時間 單號 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_kbars_order_time_by_ticket.md) |
| `get_last_position_ticket` | 取得最近下單單號 商品 魔術數字 下單方式 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_last_position_ticket.md) |
| `get_market_info` | 取得市場資訊 商品 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_market_info.md) |
| `get_mqlInfoInteger` | 取得MQL程式資料(int) 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_mqlInfoInteger.md) |
| `get_order_info` | 用單號取得單筆下單資料(double) 單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_order_info.md) |
| `get_order_info_string` | 用單號取得單筆下單資料(string) 單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_order_info_string.md) |
| `get_order_ticket_by_position` | 用下單順序取得 下單單號 商品 第 筆 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_order_ticket_by_position.md) |
| `get_pending_order_info` | 取得商品掛單資料(double) 商品 魔術數字 掛單方式 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_pending_order_info.md) |
| `get_pending_order_info_by_position` | 用掛單順序取得 掛單單號 商品 第 筆 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_pending_order_info_by_position.md) |
| `get_pending_order_info_by_ticket` | 取得商品掛單資料(double) 單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_pending_order_info_by_ticket.md) |
| `get_pending_order_integer_by_ticket` | 取得商品掛單資料(int/long/datetime) 單號 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_pending_order_integer_by_ticket.md) |
| `get_percentage_price_move_back` | 最高/最低價格縮回百分比 頂點價格 基準價格 以買賣價計算 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_percentage_price_move_back.md) |
| `get_pip_point` | 商品最小報價點 商品 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_pip_point.md) |
| `get_position_high_low_price` | 取得最高或最低下單價格 商品 魔術數字 下單方式 應用價格 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_position_high_low_price.md) |
| `get_position_high_low_ticket` | 取得最高或最低下單價格單號 商品 魔術數字 下單方式 應用價格 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_position_high_low_ticket.md) |
| `get_positions_total_profits` | 取得所有筆數總利潤 商品 魔術數字 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_positions_total_profits.md) |
| `get_sell_order_total` | 取得空單部位資料 商品 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_sell_order_total.md) |
| `get_sell_order_total_counts` | 空單 目前筆數 商品 魔術數字 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_sell_order_total_counts.md) |
| `get_sell_order_total_info` | 取得空單部位資料 商品 魔術數字 型別 計算方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_sell_order_total_info.md) |
| `get_slippage` | 取得目前商品 滑點 商品 最大滑點 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_slippage.md) |
| `get_specified_datetime` | 取得 指定時間 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_specified_datetime.md) |
| `get_string_to` | 轉換型別 字串 到 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_string_to.md) |
| `get_symbol_info_double` | 取得商品資料(double) 商品 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_double.md) |
| `get_symbol_info_integer` | 取得商品資料(long/int) 商品 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_integer.md) |
| `get_symbol_info_session_quote_datetime` | 取得商品開放報價時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_session_quote_datetime.md) |
| `get_symbol_info_session_quote_datetime1` | 取得商品開放報價時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_session_quote_datetime1.md) |
| `get_symbol_info_session_trade_datetime` | 取得商品開放交易時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_session_trade_datetime.md) |
| `get_symbol_info_session_trade_datetime1` | 取得商品開放交易時段(datetime) 商品 星期(1,2,3,4,5,6,0) 時段索引值 時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_session_trade_datetime1.md) |
| `get_symbol_info_string` | 取得商品資料(string) 商品 型別 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_info_string.md) |
| `get_symbol_name_by_index` | 取得交易商品名稱 位置順序 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_symbol_name_by_index.md) |
| `get_tick_count` | 讀取毫秒數 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_tick_count.md) |
| `get_total_available_symbols` | 取得可用交易商品數量 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_total_available_symbols.md) |
| `global_variable_delete_all` | 刪除全部總體(終端)變數 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/global_variable_delete_all.md) |
| `global_variable_get` | 取得總體(終端)變數 變數名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/global_variable_get.md) |
| `global_variable_set` | 總體(終端)變數設定 變數名稱 數值 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/global_variable_set.md) |
| `history_deal_entry_types` | (MT5)歷史成交進出類型 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_deal_entry_types.md) |
| `history_deal_reason` | (MT5)歷史成交原因 | mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_deal_reason.md) |
| `history_deal_types` | (MT5)歷史成交方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_deal_types.md) |
| `history_order_reason` | (MT5)歷史訂單原因 | mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_order_reason.md) |
| `history_order_state` | (MT5)歷史訂單狀態 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_order_state.md) |
| `history_order_type` | (MT5)歷史訂單方式 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_order_type.md) |
| `history_order_type_filling` | (MT5)歷史訂單成交量執行方式 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_order_type_filling.md) |
| `history_order_type_time` | (MT5)歷史訂單有效期間 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/history_order_type_time.md) |
| `ifttt_send_messages` | IFTTT發送訊息 雲端服務 KEY(授權碼) Event Name(事件名稱) 數值1 數值2 數值3 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/ifttt_send_messages.md) |
| `indicator1_adx` | ADX 指標 商品 時間週期 平均週期 模式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_adx.md) |
| `indicator1_bband` | 布林通道指標 商品 時間週期 平均週期 偏差值 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_bband.md) |
| `indicator1_bears_power` | 熊力指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_bears_power.md) |
| `indicator1_bulls_power` | 牛力指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_bulls_power.md) |
| `indicator1_cci` | CCI 指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_cci.md) |
| `indicator1_envelopes` | Envelopes指標 商品 時間週期 平均週期 偏差值 MA方式 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_envelopes.md) |
| `indicator1_force` | Force 指標 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_force.md) |
| `indicator1_kd` | KD隨機指標 商品 時間週期 K週期 D週期 減速值 MA方式 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_kd.md) |
| `indicator1_ma` | 指標 MA 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_ma.md) |
| `indicator1_macd` | MACD 指標 商品 時間週期 快速週期 慢速週期 訊號週期 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_macd.md) |
| `indicator1_momentum` | 動能 指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_momentum.md) |
| `indicator1_mt5_ama` | 自適應移動平均線(MT5) 商品 時間週期 平均週期 快速週期 慢速週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_ama.md) |
| `indicator1_mt5_chaikin` | 蔡金擺動指標(MT5) 商品 時間週期 快速週期 慢速週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_chaikin.md) |
| `indicator1_mt5_dema` | 雙指數移動平均線(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_dema.md) |
| `indicator1_mt5_frama` | 分形自適應移動平均線(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_frama.md) |
| `indicator1_mt5_tema` | 三次指數移動平均線(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_tema.md) |
| `indicator1_mt5_trix` | 三次指數移動平均數震盪指標(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_trix.md) |
| `indicator1_mt5_vidya` | 可變指數動態平均線(MT5) 商品 時間週期 CMO週期 EMA週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_mt5_vidya.md) |
| `indicator1_osma` | OsMA指標 商品 時間週期 快速週期 慢速週期 訊號週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_osma.md) |
| `indicator1_rsi` | RSI 指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_rsi.md) |
| `indicator1_standard_dev` | 標準偏差指標 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_standard_dev.md) |
| `indicator2_bband` | 布林通道指標 商品 時間週期 平均週期 偏差值 平移 應用價格 模式 K棒前移 位置 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator2_bband.md) |
| `indicator_ac` | 加速震盪指標 商品 時間週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_ac.md) |
| `indicator_ad` | AD 指標 商品 時間週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_ad.md) |
| `indicator_adx` | ADX 指標 商品 時間週期 平均週期 模式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_adx.md) |
| `indicator_alligator` | 鱷魚線指標 商品 時間週期 下颚週期(藍線) 下颚位移 牙齒週期(紅線) 牙齒位移 嘴唇週期(綠線) 嘴唇位移 MA方式 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_alligator.md) |
| `indicator_atr` | ATR 指標 商品 時間週期 平均週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_atr.md) |
| `indicator_awesome` | AO 震盪指標 商品 時間週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_awesome.md) |
| `indicator_bband` | 布林通道指標 商品 時間週期 平均週期 偏差值 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_bband.md) |
| `indicator_bears_power` | 熊力指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_bears_power.md) |
| `indicator_bulls_power` | 牛力指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_bulls_power.md) |
| `indicator_bwmfi` | MFI指標 商品 時間週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_bwmfi.md) |
| `indicator_cci` | CCI 指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_cci.md) |
| `indicator_custom` | 自定義指標 商品 時間週期 指標名稱 資料索引值 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_custom.md) |
| `indicator_demarker` | DeMarker 指標 商品 時間週期 平均週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_demarker.md) |
| `indicator_envelopes` | Envelopes指標 商品 時間週期 平均週期 偏差值 MA方式 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_envelopes.md) |
| `indicator_force` | Force 指標 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_force.md) |
| `indicator_fractal` | 分形指標 商品 時間週期 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_fractal.md) |
| `indicator_gator` | 鱷魚震盪指標 商品 時間週期 下颚週期(藍線) 下颚位移 牙齒週期(紅線) 牙齒位移 嘴唇週期(綠線) 嘴唇位移 MA方式 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_gator.md) |
| `indicator_ichimoku` | Ichimoku指標 商品 時間週期 Tenkan Sen週期 Kijun Sen週期 Senkou SpanB週期 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_ichimoku.md) |
| `indicator_kd` | KD隨機指標 商品 時間週期 K週期 D週期 減速值 MA方式 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_kd.md) |
| `indicator_ma` | 指標 MA 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_ma.md) |
| `indicator_macd` | MACD 指標 商品 時間週期 快速週期 慢速週期 訊號週期 應用價格 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_macd.md) |
| `indicator_mfi` | 資金流向指標 商品 時間週期 平均週期 應用手數 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mfi.md) |
| `indicator_momentum` | 動能 指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_momentum.md) |
| `indicator_mt5_ADXWilder` | ADX Wilder指標(MT5) 商品 時間週期 平均週期 模式 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_ADXWilder.md) |
| `indicator_mt5_ama` | 自適應移動平均線(MT5) 商品 時間週期 平均週期 快速週期 慢速週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_ama.md) |
| `indicator_mt5_chaikin` | 蔡金擺動指標(MT5) 商品 時間週期 快速週期 慢速週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_chaikin.md) |
| `indicator_mt5_dema` | 雙指數移動平均線(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_dema.md) |
| `indicator_mt5_frama` | 分形自適應移動平均線(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_frama.md) |
| `indicator_mt5_tema` | 三次指數移動平均線(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_tema.md) |
| `indicator_mt5_trix` | 三次指數移動平均數震盪指標(MT5) 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_trix.md) |
| `indicator_mt5_vidya` | 可變指數動態平均線(MT5) 商品 時間週期 CMO週期 EMA週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_mt5_vidya.md) |
| `indicator_obv` | 平衡交易量指標 商品 時間週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_obv.md) |
| `indicator_osma` | OsMA指標 商品 時間週期 快速週期 慢速週期 訊號週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_osma.md) |
| `indicator_rsi` | RSI 指標 商品 時間週期 平均週期 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_rsi.md) |
| `indicator_rvi` | RVI 指標 商品 時間週期 平均週期 模式 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_rvi.md) |
| `indicator_sar` | Parabolic SAR指標 商品 時間週期 加速因子(STEP) 最大值(MAX STEP) K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_sar.md) |
| `indicator_standard_dev` | 標準偏差指標 商品 時間週期 平均週期 MA方式 應用價格 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_standard_dev.md) |
| `indicator_volumes` | 交易量指標 商品 時間週期 應用手數 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_volumes.md) |
| `indicator_wpr` | 威廉WPR指標 商品 時間週期 平均週期 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator_wpr.md) |
| `indicators_cross_2lines_check` | 是否兩指標線互相穿越 L1 K棒1指標值 L1 K棒2指標值 L2 K棒1指標值 L2 K棒2指標值 穿越方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicators_cross_2lines_check.md) |
| `kill_timer` | 移除定時器 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/kill_timer.md) |
| `line_notify_messages` | LINE Notify訊息通知 權杖(Token) 訊息 圖組編號(ID) 貼圖編號(ID) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/line_notify_messages.md) |
| `linebot_messages` | LINE Notify訊息通知 權杖(Token) 使用者編號(User ID) 訊息 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/linebot_messages.md) |
| `linebot_stickers` | LINE Notify訊息通知 權杖(Token) 使用者編號(User ID) 圖組編號(ID) 貼圖編號(ID) | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/linebot_stickers.md) |
| `lists_Get_Maximum` | 陣列內容最大數值位置 陣列 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_Get_Maximum.md) |
| `lists_Get_Minimum` | 陣列內容最小數值位置 陣列 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_Get_Minimum.md) |
| `lists_copy` | 陣列內容複製 陣列 複製到 陣列 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_copy.md) |
| `lists_create_empty` | 建立空陣列 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_create_empty.md) |
| `lists_create_with` | 使用這些值建立陣列 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_create_with.md) |
| `lists_fill` | 陣列重複填滿數值 陣列 數值 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_fill.md) |
| `lists_getIndex` | 陣列 的第 項 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_getIndex.md) |
| `lists_getSublist` | 陣列 取得子陣列 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_getSublist.md) |
| `lists_indexOf` | 陣列 找出 項目出現 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_indexOf.md) |
| `lists_isEmpty` | 值為空 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_isEmpty.md) |
| `lists_length` | 陣列長度 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_length.md) |
| `lists_repeat` | 建立陣列使用項目 重複 次數 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_repeat.md) |
| `lists_reverse` | 反轉 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_reverse.md) |
| `lists_setIndex` | 陣列 的第 項賦值為 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_setIndex.md) |
| `lists_setSize` | 陣列 設定長度 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_setSize.md) |
| `lists_sort_ascend` | 陣列內容由小到大排序 陣列 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_sort_ascend.md) |
| `lists_sort_descend` | 陣列內容由大到小排序 陣列 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_sort_descend.md) |
| `lists_split` | 用分隔符 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/lists_split.md) |
| `logic_boolean` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_boolean.md) |
| `logic_compare` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_compare.md) |
| `logic_negate` | 非 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_negate.md) |
| `logic_null` | 空 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_null.md) |
| `logic_operation` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_operation.md) |
| `logic_return` | 返回主程式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_return.md) |
| `math_arithmetic` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_arithmetic.md) |
| `math_max` | 取得兩數最大值 數值 數值 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_max.md) |
| `math_min` | 取得兩數最小值 數值 數值 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_min.md) |
| `math_modulo` | 取餘數自 ÷ | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_modulo.md) |
| `math_number` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_number.md) |
| `math_random` | 取隨機整數介於 0 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_random.md) |
| `math_random_int` | 取隨機整數介於 (低) 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_random_int.md) |
| `math_single` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_single.md) |
| `math_trig` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_trig.md) |
| `messagebox_info` | 打開訊息視窗 抬頭 訊息內容 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/messagebox_info.md) |
| `mql4_ondeinit` | 結束設定OnDeinit() | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql4_ondeinit.md) |
| `mql4_ontimer` | 定時器 OnTimer() 秒 執行內容 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql4_ontimer.md) |
| `mql4_setup` | 參數宣告 初始設定OnInit() 主程式OnTick() | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql4_setup.md) |
| `mql4script_setup` | 參數宣告 主程式OnStart() | mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql4script_setup.md) |
| `mql_TesterStatistics` | 優化統計資料 型別 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql_TesterStatistics.md) |
| `mql_onTester` | 優化自定義績效函數OnTester() 回傳 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql_onTester.md) |
| `mql_onchartevent` | 回測模式 圖形驅動事件(onChartEvent) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql_onchartevent.md) |
| `object_ChartTimePriceToXY` | 時間價格轉成圖表座標 時間 價格 角落 座標 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_ChartTimePriceToXY.md) |
| `object_ChartXYToTimePrice` | 圖表座標轉成時間價格 X座標 Y座標 角落 時間/價格 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_ChartXYToTimePrice.md) |
| `object_Picture_503` | 建立貼圖 編號 檔案名稱(.bmp) 角落 水平位置 垂直位置 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_Picture_503.md) |
| `object_Picture_917` | 建立貼圖 編號 檔案名稱(.bmp) 角落 水平位置 垂直位置 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_Picture_917.md) |
| `object_arrow_draw` | 建立特殊符號 符號名稱 時間 價格 符號位置 符號碼 寬度 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_arrow_draw.md) |
| `object_button_create` | 建立按鈕 編號 名稱 角落 水平位置 垂直位置 字體大小 背景顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_create.md) |
| `object_button_create_502` | 建立按鈕 編號 名稱 角落 水平位置 垂直位置 寬度 字體大小 背景顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_create_502.md) |
| `object_button_create_503` | 建立按鈕 編號 名稱 角落 水平位置 垂直位置 寬度 字型 字體大小 文字顏色 背景顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_create_503.md) |
| `object_button_create_917` | 建立按鈕 編號 名稱 角落 水平位置 垂直位置 寬度 字體大小 文字顏色 背景顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_create_917.md) |
| `object_button_delete` | 刪除按鈕物件 編號 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_delete.md) |
| `object_button_delete_503` | 刪除按鈕物件 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_delete_503.md) |
| `object_button_function` | 建立按鈕 回測模式 編號 名稱 角落 水平位置 垂直位置 字體大小 背景顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_function.md) |
| `object_button_pressed_503` | 按下按鈕執行 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_pressed_503.md) |
| `object_button_pressed_917` | 按下按鈕執行 編號 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_pressed_917.md) |
| `object_button_update` | 更新按鈕顏色 編號 文字顏色 背景顏色 字型 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_button_update.md) |
| `object_checkbox_503` | 建立複選框 編號 顯示文字 水平位置 垂直位置 寬度 顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_checkbox_503.md) |
| `object_checkbox_917` | 建立複選框 編號 顯示文字 水平位置 垂直位置 寬度 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_checkbox_917.md) |
| `object_checkbox_delete_503` | 刪除複選框物件 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_checkbox_delete_503.md) |
| `object_checkbox_update` | 更新複選框狀態 編號 狀態 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_checkbox_update.md) |
| `object_checkbox_update_917` | 更新複選框狀態 編號 狀態 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_checkbox_update_917.md) |
| `object_combo1_checkbox_edit` | (組合1)複選框及編輯欄位 編號 顯示文字 水平位置 垂直位置 標籤寬 欄位寬 文字顏色 字體大小 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_combo1_checkbox_edit.md) |
| `object_combo1_checkbox_edit_503` | (組合1)複選框及編輯欄位 編號 顯示文字 水平位置 垂直位置 標籤寬 欄位寬 文字顏色 背景顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_combo1_checkbox_edit_503.md) |
| `object_combo2_label_edit` | (組合2)標籤及編輯欄位 編號 顯示文字 水平位置 垂直位置 標籤寬 欄位寬 文字顏色 字體大小 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_combo2_label_edit.md) |
| `object_combo2_label_edit_503` | (組合2)標籤及編輯欄位 編號 顯示文字 水平位置 垂直位置 標籤寬 欄位寬 文字顏色 背景顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_combo2_label_edit_503.md) |
| `object_combo2_label_edit_get_503` | (組合2)取得 編輯欄位資料 編號 物件 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_combo2_label_edit_get_503.md) |
| `object_combo2_label_edit_set_503` | (組合2)更新 標籤文字 編號 顯示文字 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_combo2_label_edit_set_503.md) |
| `object_delete_all` | 清除所有圖表物件 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_delete_all.md) |
| `object_dialog_create_503` | 建立方形面板 編號 面板名稱 角落 水平位置 垂直位置 寬度 高度 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_dialog_create_503.md) |
| `object_dialog_create_917` | 建立方形面板 編號 面板名稱 角落 水平位置 垂直位置 寬度 高度 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_dialog_create_917.md) |
| `object_edit_delete` | 刪除編輯物件 編號 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_delete.md) |
| `object_edit_delete_503` | 刪除編輯物件 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_delete_503.md) |
| `object_edit_function` | 建立編輯欄位 編號 角落 水平位置 垂直位置 欄位寬 字體大小 背景顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_function.md) |
| `object_edit_function_503` | 建立編輯欄位 編號 角落 水平位置 垂直位置 欄位寬 字型 字體大小 文字顏色 背景顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_function_503.md) |
| `object_edit_function_917` | 建立編輯欄位 編號 角落 水平位置 垂直位置 欄位寬 字體大小 文字顏色 背景顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_function_917.md) |
| `object_edit_update` | 更新編輯欄位文字 編號 顯示文字 字型 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_update.md) |
| `object_edit_update_917` | 更新編輯欄位文字 編號 顯示文字 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_edit_update_917.md) |
| `object_ellipse_draw` | 建立橢圓形物件 名稱 時間 價格 時間 價格 時間 價格 填滿 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_ellipse_draw.md) |
| `object_fibo_line_draw` | 建立FIBO曲線 名稱 時間 價格 時間 價格 寬度 樣式 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_fibo_line_draw.md) |
| `object_fibo_line_get` | 取得FIBO曲線數值 名稱 切割率 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_fibo_line_get.md) |
| `object_fibo_line_ratio_get` | 取得FIBO曲線數值 名稱 切割率 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_fibo_line_ratio_get.md) |
| `object_fibo_ratio` |  | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_fibo_ratio.md) |
| `object_get_object_name_by_index` | 取得圖表中物件名稱 位置順序 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_get_object_name_by_index.md) |
| `object_get_total_objects` | 取得圖表中物件數量 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_get_total_objects.md) |
| `object_horizontal_line_draw` | 畫一條水平線 水平線名稱 價格 寬度 樣式 可移動 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_horizontal_line_draw.md) |
| `object_horizontal_line_get` | 取得圖表中水平線價格 水平線名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_horizontal_line_get.md) |
| `object_label_delete` | 刪除標籤物件 編號 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_delete.md) |
| `object_label_delete_503` | 刪除標籤物件 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_delete_503.md) |
| `object_label_display` | 建立標籤 編號 顯示文字 角落 水平位置 垂直位置 字體大小 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_display.md) |
| `object_label_display_503` | 建立標籤 編號 顯示文字 角落 水平位置 垂直位置 字型 字體大小 顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_display_503.md) |
| `object_label_display_917` | 建立標籤 編號 顯示文字 角落 水平位置 垂直位置 字型 字體大小 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_display_917.md) |
| `object_label_set_503` | 更新標籤文字 編號 顯示文字 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_set_503.md) |
| `object_label_set_917` | 更新標籤文字 編號 顯示文字 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_set_917.md) |
| `object_label_update_color` | 更新標籤文字 編號 顯示文字 字型 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_label_update_color.md) |
| `object_line_delete` | 刪除圖表上線條物件 名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_line_delete.md) |
| `object_line_display_503` | 畫區隔線 編號 區隔線字元 角落 水平位置 垂直位置 寬度 顏色 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_line_display_503.md) |
| `object_line_display_917` | 畫區隔線 編號 區隔線字元 角落 水平位置 垂直位置 寬度 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_line_display_917.md) |
| `object_panel1` | 面板1號 編號 外框 名稱 水平位置 垂直位置 按鈕(1) 按鈕(1)顏色 按鈕(2) 按鈕(2)顏色 標籤(1) 編輯(1) 標籤(2) 標籤(3) 編輯(2) 標籤(4) | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel1.md) |
| `object_panel1_button_pressed` | 面板1號 編號 按下按鈕執行 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel1_button_pressed.md) |
| `object_panel1_delete` | 刪除面板1號 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel1_delete.md) |
| `object_panel1_edit_get` | 取得面板1號 編號 物件 回傳 型別 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel1_edit_get.md) |
| `object_panel1_label_set` | 更新面板1號 編號 物件 顯示文字 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel1_label_set.md) |
| `object_panel2` | 面板2號 編號 外框 名稱 水平位置 垂直位置 顏色 標籤(1) 標籤(2) 標籤(3) 標籤(4) 標籤(5) 標籤(6) | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel2.md) |
| `object_panel2_delete` | 刪除面板2號 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel2_delete.md) |
| `object_panel2_label_set` | 更新面板2號 編號 物件 顯示文字 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_panel2_label_set.md) |
| `object_picture_delete_503` | 刪除圖片物件 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_picture_delete_503.md) |
| `object_radio_button_set` | 建立單選框 編號 顯示文字 水平位置 垂直位置 寬度 顏色 | mt4 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_radio_button_set.md) |
| `object_rectangle_draw` | 建立矩形方塊 編號 角落 水平位置 垂直位置 寬度 高度 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_rectangle_draw.md) |
| `object_rectangle_draw_917` | 建立矩形方塊 編號 角落 水平位置 垂直位置 寬度 高度 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_rectangle_draw_917.md) |
| `object_rectangle_time_draw` | 利用時間價格建立矩形方塊 名稱 時間 價格 時間 價格 顏色 填滿 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_rectangle_time_draw.md) |
| `object_rectangle_update` | 更新矩形方塊 編號 寬度 高度 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_rectangle_update.md) |
| `object_rectangle_update_917` | 更新矩形方塊 編號 寬度 高度 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_rectangle_update_917.md) |
| `object_spinedit_503` | 旋轉編輯框 編號 水平位置 垂直位置 欄位寬 最小數值 最大數值 初始數值 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_spinedit_503.md) |
| `object_trend_line_draw` | 畫一條趨勢線 趨勢線名稱 時間 價格 時間 價格 寬度 樣式 延伸 可移動 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_trend_line_draw.md) |
| `object_trend_line_get` | 取得圖表中趨勢線價格 趨勢線名稱 K棒前移 位置 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_trend_line_get.md) |
| `object_triangle_draw` | 建立三角形物件 名稱 時間 價格 時間 價格 時間 價格 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_triangle_draw.md) |
| `object_vertical_line_draw` | 畫一條垂直線 垂直線名稱 時間 寬度 樣式 可移動 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_vertical_line_draw.md) |
| `object_vertical_line_get` | 取得圖表中垂直線時間 垂直線名稱 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/object_vertical_line_get.md) |
| `objects_combo_delete` | 刪除複合物件 名稱 編號 | mt4, mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/objects_combo_delete.md) |
| `objects_delete` | 刪除物件 名稱 編號 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/objects_delete.md) |
| `objects_delete_917` | 刪除物件 名稱 編號 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/objects_delete_917.md) |
| `ontimer_milliseconds` | 定時器 OnTimer() 毫秒 執行內容 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/ontimer_milliseconds.md) |
| `order_close_by_ticket` | 平倉依單號 單號 手數 最大滑點 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_close_by_ticket.md) |
| `order_modify` | 修改停損停利 商品 魔術數字 下單方式 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_modify.md) |
| `order_modify_by_open_market_price` | 修改停損停利 商品 魔術數字 下單方式 依照價格 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_modify_by_open_market_price.md) |
| `order_modify_by_symbol` | 修改停損停利 商品 魔術數字 下單方式 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_modify_by_symbol.md) |
| `order_modify_by_ticket` | 修改停損停利 單號 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_modify_by_ticket.md) |
| `order_modify_by_ticket_magic` | 修改停損停利 單號 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_modify_by_ticket_magic.md) |
| `order_modify_by_ticket_open_market_price` | 修改停損停利 單號 依照價格 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/order_modify_by_ticket_open_market_price.md) |
| `ordercloseby_all_trades` | 所有筆數透過相反持倉來平倉 商品 魔術數字 平倉剩餘部位 顏色 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/ordercloseby_all_trades.md) |
| `ordercloseby_ticket` | 透過相反持倉來平倉(OrderCloseBy) 單號 1 單號 2 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/ordercloseby_ticket.md) |
| `pending_order_Ret` | 掛單 商品 魔術數字 掛單方式 手數 價格 最大滑點 停損 停利 註解 有效期 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/pending_order_Ret.md) |
| `pending_order_modify_by_ticket` | 修改掛單價格 單號 掛單(價格) 停損 停利 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/pending_order_modify_by_ticket.md) |
| `pending_order_noRet` | 掛單 商品 魔術數字 掛單方式 手數 價格 最大滑點 停損 停利 註解 有效期 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/pending_order_noRet.md) |
| `pending_order_pip_price` | 掛單 商品 魔術數字 掛單方式 手數 價格 最大滑點 停損 停利 註解 有效期 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/pending_order_pip_price.md) |
| `pending_order_pip_price_noRet` | 掛單 商品 魔術數字 掛單方式 手數 價格 最大滑點 停損 停利 註解 有效期 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/pending_order_pip_price_noRet.md) |
| `price_ask` | 商品賣出價(Ask) 商品 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/price_ask.md) |
| `price_bid` | 商品買入價(Bid) 商品 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/price_bid.md) |
| `prices_to_points` | 價格1 減去 價格2 (返回點差) 商品 價格1 價格2 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/prices_to_points.md) |
| `print_info` | 輸出訊息 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/print_info.md) |
| `procedures_callnoreturn` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/procedures_callnoreturn.md) |
| `procedures_callreturn` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/procedures_callreturn.md) |
| `procedures_defnoreturn` | 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/procedures_defnoreturn.md) |
| `procedures_defreturn` | 到 回傳 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/procedures_defreturn.md) |
| `procedures_ifreturn` | 如果 回傳 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/procedures_ifreturn.md) |
| `property_info` | 程式屬性說明 版權 連結網站 版本 描述 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/property_info.md) |
| `round_off_number` | 取得該數值小數點後位數 數值 第幾位 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/round_off_number.md) |
| `sell_order_Ret` | 空單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_Ret.md) |
| `sell_order_close` | 空單平倉 商品 魔術數字 手數 最大滑點 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_close.md) |
| `sell_order_close_all` | 全部空單平倉 商品 魔術數字 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_close_all.md) |
| `sell_order_noRet` | 空單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_noRet.md) |
| `sell_order_send_pip_price` | 空單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_send_pip_price.md) |
| `sell_order_send_pip_price_noRet` | 空單下單 商品 魔術數字 手數 最大滑點 停損 停利 註解 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_send_pip_price_noRet.md) |
| `telegram_push_messages` | Telegram 推播訊息 Token(權杖) Chat ID 訊息 | mt4, mt5 | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/telegram_push_messages.md) |
| `text` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text.md) |
| `text_StringSubstr` | 回傳子字串 自字串 取得一段字串從位置 字串長度 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_StringSubstr.md) |
| `text_String_CR_NL` | 字串結尾(CR&NL) | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_String_CR_NL.md) |
| `text_append` | 在字串 後加入文字 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_append.md) |
| `text_changeCase` | 轉成 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_changeCase.md) |
| `text_charAt` | 的字元在字串 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_charAt.md) |
| `text_find` | 回傳字串的位置 在字串 從字元開始位置 欲搜尋子字串 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_find.md) |
| `text_getSubstring` | 自字串 到 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_getSubstring.md) |
| `text_indexOf` | 在字串 尋找 出現的字串 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_indexOf.md) |
| `text_isEmpty` | 為空 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_isEmpty.md) |
| `text_join` | 建立字串使用 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_join.md) |
| `text_length` | 字串長度 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_length.md) |
| `text_print` | 印出 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_print.md) |
| `text_prompt` | 輸入 並顯示提示訊息 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_prompt.md) |
| `text_trim` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text_trim.md) |
| `time_sleep` | 暫時停止一段時間 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/time_sleep.md) |
| `time_sleep_seconds` | 暫時停止一段時間 單位 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/time_sleep_seconds.md) |
| `timer_check` | 倒數計時器 秒 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/timer_check.md) |
| `total_buy_order_count` | 多單 目前筆數 商品 魔術數字 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/total_buy_order_count.md) |
| `total_buy_sell_order_count` | 多單及空單 目前總筆數 商品 魔術數字 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/total_buy_sell_order_count.md) |
| `total_pending_order_count` | 掛單 目前筆數 商品 魔術數字 掛單方式 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/total_pending_order_count.md) |
| `total_sell_order_count` | 空單 目前筆數 商品 魔術數字 | mt5, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/total_sell_order_count.md) |
| `trailing_stop_symbol_pip_price` | 移動停損 商品 魔術數字 下單方式 停損距離 每 點移動 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/trailing_stop_symbol_pip_price.md) |
| `trailing_stop_ticket_pip_price` | 依單號移動停損 單號 停損距離 每 點移動 顏色 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/trailing_stop_ticket_pip_price.md) |
| `variables_declare` | 宣 告 當 資料 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_declare.md) |
| `variables_get` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_get.md) |
| `variables_get_dynamic` |  | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_get_dynamic.md) |
| `variables_set` | 賦值 為 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_set.md) |
| `variables_set_dynamic` | 賦值 為 | mt4, mt5, mt4script, mt5script | [讀取](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_set_dynamic.md) |
