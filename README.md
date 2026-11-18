# 東華醫院歷史場景｜互動 3D 展示

這個靜態網頁以 Three.js 展示七個模型：1870 年創院、1870 年牌樓、1903 年擴建、1933 年及以後、1933 年後牌樓、Tung Wah Old，以及醫院與寺廟周邊街道圖與人流動畫。動畫場景會自動播放，頁面提供暫停及播放控制。

## GitHub Pages 部署

1. 將本資料夾內的 `index.html`、`assets/` 和 `README.md` 上傳至 GitHub repository 根目錄（或同一個資料夾）。
2. 在 repository 的 **Settings → Pages**，選擇部署分支及根目錄，儲存後即可使用 GitHub Pages 網址。
3. 開啟網站後可切換場景、拖曳旋轉模型、滾輪縮放；按鈕可重設視角、自動旋轉、播放／暫停動畫及全螢幕。

網頁載入 `assets/` 內的七個 GLB 模型。網頁使用 jsDelivr 上的 Three.js CDN，因此瀏覽器需要網絡連線。請透過 GitHub Pages 或本機 HTTP 伺服器開啟；直接雙擊 `index.html` 可能會被瀏覽器的本機檔案安全政策阻擋。

本機預覽（在此資料夾執行）：

```bash
python3 -m http.server 8000
```

然後開啟 `http://localhost:8000`。
