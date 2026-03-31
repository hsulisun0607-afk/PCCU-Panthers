# PCCU Panthers Team System

## 部署到 GitHub Pages（免費，5分鐘完成）

### 步驟

1. **建立 GitHub 帳號**（如果還沒有）
   → https://github.com

2. **新建 Repository**
   - 點右上角 `+` → `New repository`
   - Repository name：`pccu-panthers`
   - 設定為 **Public**
   - 點 `Create repository`

3. **上傳這個資料夾的所有檔案**
   - 點 `uploading an existing file`
   - 把這個資料夾裡的 **4 個檔案** 全部拖進去：
     - `index.html`
     - `manifest.json`
     - `sw.js`
     - `icon-192.png`
     - `icon-512.png`
   - 點 `Commit changes`

4. **開啟 GitHub Pages**
   - 進入 Repository → `Settings`
   - 左側選 `Pages`
   - Source 選 `Deploy from a branch`
   - Branch 選 `main`，資料夾選 `/ (root)`
   - 點 `Save`

5. **等待約 1–2 分鐘**，網址會出現：
   `https://你的帳號名稱.github.io/pccu-panthers`

---

## iOS 安裝方式

1. 用 **Safari** 開啟上面的網址
2. 點底部 **分享按鈕**（方框+箭頭）
3. 選 **「加入主畫面」**
4. 名稱輸入 `Panthers` → 點 **新增**
5. 主畫面出現 App 圖示，點開後全螢幕顯示 ✓

---

## 注意事項
- 必須用 **Safari** 才能安裝（Chrome 在 iOS 不支援 PWA 安裝）
- 安裝後完全離線可用
- 每次更新系統後重新上傳 `index.html` 即可
