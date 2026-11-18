# 1870 東華三院創院場景｜互動 3D 展示

這個靜態網頁以 Three.js 顯示由原始 Blender 場景匯出的 GLB 模型，支援桌面及手機操作。

## GitHub Pages 部署

1. 將本資料夾內的 `index.html`、`assets/` 和 `README.md` 上傳至 GitHub repository 根目錄（或同一個資料夾）。
2. 在 repository 的 **Settings → Pages**，選擇部署分支及根目錄，儲存後即可使用 GitHub Pages 網址。
3. 開啟網站後可拖曳旋轉模型、滾輪縮放；按鈕可重設視角、自動旋轉及全螢幕。

模型以 `assets/tung-wah-1870.glb` 載入。網頁使用 jsDelivr 上的 Three.js CDN，因此瀏覽器需要網絡連線。請透過 GitHub Pages 或本機 HTTP 伺服器開啟；直接雙擊 `index.html` 可能會被瀏覽器的本機檔案安全政策阻擋。

本機預覽（在此資料夾執行）：

```bash
python3 -m http.server 8000
```

然後開啟 `http://localhost:8000`。
