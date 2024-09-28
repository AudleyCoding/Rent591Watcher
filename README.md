# 591 租屋網 新屋通知機器人 2024版
<a href="url"><img src="https://s2.loli.net/2024/09/29/18PBSlfcI6MhbtE.jpg" width="400" ></a>


- 從網路上歷年來不斷更迭的爬蟲程式碼可以知道 591 一直不遺餘力的打擊爬蟲，我相信過不久爬蟲方式又會改變。
- 首先想謝謝網路上各位前輩的努力，尤其是 IT空間-Jia 大大，我從中借鑒了許多程式碼，謝謝 ><
- 總而言之，如果想要在每天 8/16/24 點收到最新的租屋資訊，請跟著這個步驟做下去^^

## 1. 確認 591 租屋網的網址
如下圖所示，可以根據偏好設定 591 租屋網的的條件，並且記住設定後的 591 網址
<a href="url"><img src="https://s2.loli.net/2024/09/29/v78P2YcDpoL5mkE.png" width="600" ></a>


## 2. 申請 LINE 金鑰
這樣才可以傳訊息給自己，申請方式請參考: https://notify-bot.line.me/zh_TW


## 3. 複製這個專案到自己的帳號
- 專案地址：[github/Rent591Watcher](https://github.com/ryk001/Rent591Watcher/tree/main)
- 點擊右上角 Fork 專案至自己的帳號底下

## 4. 複製這個專案到自己的帳號
- 建立一個名為`URL`的 secret，裡面填上設定條件後的 591 網址
- 再建立一個名為`LINE_NOTIFY_TOKEN`的 secret，裡面填上 LINE Notify 的金鑰

## 5. 啟用 Actions

Actions 默認是關閉狀態，在 Fork 之後需要先手動執行一次，成功運行才會被激活。

返回項目主頁面，點擊上方的`Actions`，再點擊右側的`Rent591Watcher`，再點擊`Run workflow`

運行成功後，就大功告成啦! 有任何疑問與建議歡迎交流，我們下次見!!!
