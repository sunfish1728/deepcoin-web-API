# 鯨幣託管設定

此公開倉庫只保存不含 AI API key 的 v1 卡片設定 JSON。網頁程式在 [deepcoin-web](https://github.com/sunfish1728/deepcoin-web)，Android 程式與卡片規格在 [deepcoin](https://github.com/sunfish1728/deepcoin/blob/main/SPEC.md)。

卡片保存 v2 參照（id、key、ref）；App／網頁從 raw.githubusercontent.com 下載 JSON，核對 ID 並以卡片上的 key 合併。新上傳用隨機新檔名，不覆蓋已發布的設定。example.json 是無密鑰示範。

使用者選擇 App 共用的 GitHub token，並明確接受它可從 APK 取出、他人可能修改此倉庫。授權僅限此倉庫 Contents Read and write；token 不提交原始碼。
