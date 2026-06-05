Eatabler Expo Order - GitHub Pages / PWA 版

文件內容：
- index.html：主頁面，已內嵌產品、地區、樣式與訂單邏輯
- manifest.json：讓 Safari/瀏覽器可「加入主畫面」
- service-worker.js：離線快取
- icon-192.png / icon-512.png：主畫面圖標

上傳到 GitHub Pages：
1. 新建一個 GitHub repository，例如 eatabler-expo-order。
2. 將本文件夾內所有文件上傳到 repository 根目錄。
3. 到 Settings → Pages。
4. Source 選 Deploy from a branch。
5. Branch 選 main / root。
6. 等 GitHub 生成網址，例如：
   https://你的GitHub用戶名.github.io/eatabler-expo-order/

iPad 使用方法：
1. 展會前，在 iPad Safari 打開 GitHub Pages 網址。
2. 等頁面完整載入。
3. Safari 分享 → 加入主畫面。
4. 回到 iPad 主畫面，點 Eatabler Order 圖標，至少開啟一次。
5. 之後即使無網絡，也應可從主畫面打開使用。

重要測試：
- 請在展會前測試：加入主畫面後，開飛行模式，再打開 Eatabler Order。
- 輸入 2-3 張訂單，Export Excel / CSV，確認可以保存和打開。
- 展會期間建議每 10-20 張訂單匯出一次備份。

更新版本：
如果你修改了 index.html 後重新上傳 GitHub，請同事在有網絡時重新打開一次網頁或主畫面 App。
如仍顯示舊版本，可能需要清除網站資料或提高 service-worker.js 裡的 CACHE_NAME 版本號。
