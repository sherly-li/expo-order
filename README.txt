Eatabler Expo Order PWA FIXED

這一版修正：
- 產品資料直接內嵌在 index.html
- 地區資料直接內嵌在 index.html
- 不依賴 products.json / districts.json
- 不依賴 style.css
- GitHub Pages 只需上傳這些文件到 repository 根目錄

文件：
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

更新 GitHub Pages：
1. 刪除舊 repo 內的同名文件，或直接覆蓋。
2. 上傳本 zip 內所有文件到 repository 根目錄。
3. 等 GitHub Pages 部署完成。
4. iPad Safari 打開 github.io 網址。
5. 如仍看到舊版，請在網址後加 ?v=3，例如：
   https://你的用戶名.github.io/你的repo/?v=3

重要：
因為 PWA 有離線快取，如果之前加入過主畫面，可能會顯示舊快取。
最簡單做法：
- 先用 Safari 打開 github.io/?v=3
- 確認 package / 地址 / 產品都顯示
- 再重新加入主畫面
