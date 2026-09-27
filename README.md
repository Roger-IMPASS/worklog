# 真實工時表（iPhone 版）

## 放上 GitHub Pages
1. GitHub 新增一個 repository，例如 `worklog`，設為 Public。
2. 在 repo 頁面按 **Add file → Upload files**，把這個資料夾裡的所有檔案（含 `icons` 資料夾）拖進去，按 Commit。
3. **Settings → Pages**：Source 選 `Deploy from a branch`，Branch 選 `main` / `(root)`，Save。
4. 約 1 分鐘後網址會是 `https://<你的帳號>.github.io/worklog/`。

## 裝到 iPhone
1. 用 **Safari** 打開上面的網址（一定要 Safari）。
2. 分享按鈕 → **加入主畫面** → 加入。
3. 之後從主畫面圖示開啟，會是全螢幕、沒網路也能記錄。

## 注意
- 資料存在手機裡，不會上傳任何地方。建議每週按「匯出備份」存到「檔案」App 或 iCloud。
- 刪除主畫面圖示會連資料一起刪掉，刪除前先匯出備份。
- 之後修改 `index.html` 時，把 `sw.js` 裡的 `VERSION` 改成 `v2`、`v3`…，手機重開 app 兩次就會更新。
