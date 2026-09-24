# 濟春中藥行

苗栗通霄・濟春中藥行官方網站。

## 上傳到 GitHub Pages

1. 在 GitHub 建立新的 repository（例：`jichun`），設為 Public
2. 把這個資料夾裡的**所有檔案**上傳到 repository 根目錄（含 `img` 資料夾與 `.nojekyll`）
3. Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾 `/ (root)` → Save
4. 約 1–2 分鐘後網址會出現在同一頁：`https://你的帳號.github.io/jichun/`

## 後台入口

網址最後加上 `#jc-admin`，例：`https://你的帳號.github.io/jichun/#jc-admin`

## 檔案說明

- `index.html`：網站主程式
- `support.js`：網站執行所需元件，不可刪除
- `img/`：輪播、門市、logo 圖片
- `.nojekyll`：讓 GitHub 不要改動檔案，不可刪除

資料（商品、訂單、會員、文章）存於 Supabase 雲端資料庫，更新網站程式不會影響資料。
