# Caveduck Class Reference

純靜態網站，用來查找 Caveduck 可直接使用的既有 CSS class。

## GitHub Pages 部署

這個 repo 不需要 `npm install`、build step 或 GitHub Actions。

部署方式：

1. 進入 GitHub repo `Prysline/caveduck-class-reference`
2. 打開 `Settings -> Pages`
3. `Build and deployment` 選 `Deploy from a branch`
4. Branch 選 `main`
5. Folder 選 `/ (root)`
6. 儲存後等待 GitHub Pages 發布

預期網址：

- `https://prysline.github.io/caveduck-class-reference/`

## 更新流程

1. 修改 repo 內的靜態檔案
2. commit 並 push 到 `main`
3. 等待 GitHub Pages 重新發布

## 快取注意事項

如果線上頁面沒有更新，先檢查：

- 瀏覽器快取
- `index.html` 內對資產的版本字串

目前有版本字串的檔案：

- `styles.css?v=compare-vertical-cards-v1`
- `app.js?v=compare-vertical-cards-v2`

如果樣式或腳本有更新但線上仍顯示舊內容，應同步更新對應的 query string。
