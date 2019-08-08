# LINE BOT

# 參考
 [LINE BOT](https://medium.com/pyradise/%E4%BD%BF%E7%94%A8node-js%E5%BB%BA%E7%BD%AE%E4%BD%A0%E7%9A%84%E7%AC%AC%E4%B8%80%E5%80%8Bline-bot-590b7ba7a28a)

# 技術

- [LINE Developers](https://developers.line.biz/console/channel/1606909913/basic/)申請註冊和獲取id, channel id and token, setting for webhook 
- [LINE Business ID](https://manager.line.biz/account/@854kvvdc/setting/response) 可以設定回覆情況
- 使用webhook, 使用line 的webhook去連接到公用的https去和server端溝通
- server端透過[ngrok ](https://dashboard.ngrok.com/get-started)去把localhost連接到公用https去才可以和line的webhook溝通

# 下一步
- 整合爬蟲，讓BOT可以獲取必要資料
