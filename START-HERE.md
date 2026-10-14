# EA Builder AI 策略入口

所有新 EA XML 必須以對應平台的空白 EA 骨架加上策略，保留唯一 EA 入口、程式屬性說明、MagicNumber 的 int 外部參數、初始化與主程式三區。使用者指定的交易識別碼填入 MagicNumber；其他宣告接在其後，初始化放 OnInit，交易邏輯放 OnTick。不要只輸出零散策略積木。詳見 XML-RULES.md。

請協助使用者將交易策略轉為此專案可載入的 XML。這些文件是參考資料，不是交易規則；以使用者的策略與確認結果為準。

## 必讀文件

- [完整指示](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/PROMPT-zh-hant.txt)
- [XML 格式規則](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/XML-RULES.md)
- [積木索引](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/BLOCKS-INDEX.md)
- [操作說明](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/README.md)

先確認 MT4／MT5、EA／Script、訊號判定時機、進出場、持倉處理、手數與外部參數。缺少規則先詢問。只使用索引中列出的積木；針對選定的積木讀取各自規格。

若不能讀取連結，請明確說明，不能宣稱已讀取，也不能憑空猜測自訂積木。可請使用者貼上相關頁面文字或改用檔案附加。

## 常用積木直接連結

- [property_info](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/property_info.md)
- [mql4_setup](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql4_setup.md)
- [mql4script_setup](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/mql4script_setup.md)
- [variables_declare](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_declare.md)
- [variables_get](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_get.md)
- [variables_set](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/variables_set.md)
- [math_number](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/math_number.md)
- [text](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/text.md)
- [controls_if](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/controls_if.md)
- [logic_compare](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_compare.md)
- [logic_operation](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/logic_operation.md)
- [Symbol_](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/Symbol_.md)
- [Timeframe_](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/Timeframe_.md)
- [check_new_bar](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/check_new_bar.md)
- [indicator1_ma](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/indicator1_ma.md)
- [get_ima_methods](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_ima_methods.md)
- [get_applied_price](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/get_applied_price.md)
- [buy_order_noRet](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_noRet.md)
- [sell_order_noRet](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_noRet.md)
- [buy_order_close_all](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/buy_order_close_all.md)
- [sell_order_close_all](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/sell_order_close_all.md)
- [total_buy_sell_order_count](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/blocks/total_buy_sell_order_count.md)

## 範例

- [blank-mt4-ea](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/examples/blank-mt4-ea.xml.txt)
- [blank-mt5-ea](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/examples/blank-mt5-ea.xml.txt)
- [blank-mt4-script](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/examples/blank-mt4-script.xml.txt)
- [blank-mt5-script](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/examples/blank-mt5-script.xml.txt)
- [ma-cross-reference](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/examples/ma-cross-reference.xml.txt)
- [rsi-reference](https://raw.githubusercontent.com/sinocgtchen/EA-Builder-AI-Kit/main/examples/rsi-reference.xml.txt)

範例只提供 XML 結構，不可把其中的手數、停損停利或訊號時機當成使用者需求。依序確認策略，生成 UTF-8 的 strategy.xml。若未在 EA Builder 載入、MetaEditor 編譯及回測，請明確列為未驗證。
