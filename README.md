# Jui-Yun Hsieh 謝芮云 個人學術網站

純 HTML 單頁網站，可直接部署到 GitHub Pages，中英文切換按鈕在右上角。

## 部署步驟
1. 登入 GitHub，建立新的 public repository，名稱必須是 `你的帳號.github.io`
2. 進入 repo，點 Add file 選 Upload files，把 index.html、README.md、.nojekyll 拖進去後 Commit
3. 到 Settings 的 Pages，Source 選 Deploy from a branch，Branch 選 main 和 / (root)，按 Save
4. 約 1 到 2 分鐘後，網站會出現在 https://你的帳號.github.io

## 之後要修改的地方（搜尋 index.html）
- 照片：把 photo.jpg 一起上傳，並依檔案中的註解替換 `<span>謝</span>`
- Google Scholar、ORCID、CV 連結：把 `href="#"` 換成真正的網址
