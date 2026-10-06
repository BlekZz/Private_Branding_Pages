# Private_Branding_Pages

個人 OAuth 應用程式在 Google Auth Platform「品牌」頁需要的公開頁面（首頁、隱私權政策、服務條款），以 GitHub Pages 發布。

- 網址：https://blekzz.github.io/Private_Branding_Pages/
- 已授權網域：`blekzz.github.io`（Search Console 驗證檔放在 repo 根，檔名 `google*.html`，不可刪）
- 目前涵蓋的應用程式：`rclone-media-workspace`（GCP 專案 `media-workspace-rclone`，Drive API `drive.file`；使用方為 `Private_Media_Studio` 的 `scripts/drive-sync.mjs`）

## 新增應用程式
1. `index.html` 加一個 `<h2 id="<app>">` 段落：用途、API、scope、資料流向。
2. scope 若超出現有描述，同步改 `privacy.html` 第 1–3 節並更新日期。
3. 該 app 的 GCP 品牌頁填同一組網址（首頁可用 `#<app>` 錨點）。

## 為什麼是 public
GitHub 免費方案的 Pages 只能從 public repo 發布，而且 Google 必須能匿名讀到這些頁面。內容只有政策文字，不放任何設定或憑證。
