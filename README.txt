投籃追蹤器（Android 可安裝網頁 App）

內容：
- index.html：程式主體
- manifest.webmanifest：安裝資訊
- sw.js：離線快取

最快試用：
1. 解壓縮後，用 Chrome 開啟 index.html 可先試用基本功能。
2. 訓練紀錄存在該瀏覽器的本機儲存空間；請定期到「備份」匯出 JSON。

安裝成 Android 主畫面 App：
1. 將三個檔案放在同一個 HTTPS 網站目錄（例如自己的網站或支援靜態網站的託管服務）。
2. 用 Android Chrome 開啟該 HTTPS 網址。
3. 點 Chrome 右上角 ⋮ →「安裝應用程式」或「加到主畫面」。

注意：
- 真正的 PWA 安裝與離線快取需要 HTTPS 網址；直接開啟本機 HTML 可以測試，但不會完整啟用安裝與 Service Worker。
- 目前資料保存在單一瀏覽器/裝置，不會自動跨裝置同步。請定期匯出 JSON 備份。
- 匯入 JSON 會取代目前歷史資料。
