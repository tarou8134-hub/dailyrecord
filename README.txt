星芽待辦 · GitHub Pages / iPhone 版本

上傳到 GitHub：
1. 在 GitHub 建立一個新 repository，例如 starbud-planner。
2. 解壓 ZIP，將 index.html、manifest.webmanifest、sw.js 和三個 PNG 圖示直接上傳到 repository 根目錄；不要只上傳 ZIP。
3. 到 repository 的 Settings → Pages → Build and deployment：Source 選 Deploy from a branch，Branch 選 main，Folder 選 /(root)，然後 Save。
4. GitHub 會顯示網站網址，一般形式為 https://你的帳號.github.io/starbud-planner/ 。發佈可能需要數分鐘。

在 iPhone 開啟：
1. 用 Safari 開啟 GitHub Pages 網址。
2. 點分享按鈕 → 加入主畫面；如有「作為網頁 App 開啟」選項，將它開啟，再點加入。
3. 之後可從主畫面圖示開啟。首次載入需要網絡；載入後主要頁面可離線使用。

資料與轉移：
- 待辦、得分、英文進度都存在裝置瀏覽器本機，不會自動同步到另一部手機。
- 從舊 HTML 轉用網站前，先在舊版本按「匯出備份」，在網站按「匯入備份」。Safari 與主畫面 App 的儲存空間可能不同；在準備使用的入口匯入備份。
- 上傳到公開 GitHub Pages 的程式檔不包含你的待辦資料。不要把備份 JSON 上傳到公開 repository。
- 更新程式時，上傳新版檔案覆蓋舊檔；如果有修改 sw.js，亦請更改 CACHE_NAME 的版本號。
