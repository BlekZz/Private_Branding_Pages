# CLAUDE.md

本 repo 是公開靜態頁（首頁、隱私權政策、服務條款），以 GitHub Pages 從 main 根目錄發布，供 Google OAuth 品牌頁引用。細節見 README.md（不在此複製）。

## 注意事項
- push main 即公開上線；repo 為 public，不得放設定、憑證、本機路徑或個人聯絡資訊。
- Search Console 驗證檔（根目錄 `google*.html`）不可刪。
- 修改 `privacy.html` 的內容時，同步更新頁內日期。
- 無建置步驟：純 HTML／CSS，直接編輯後 commit。

## 文件命名與歸檔
前綴與歸檔規則依全域 canonical §5；本 repo 只用 README.md 與 `dev/handoff/`（工作狀態 lane，無進行中工作時僅留 `.gitkeep`）。

## 知識歸檔路由表
| 洞見類型 | 歸檔目標 |
|----------|----------|
| Schema／事實類知識 | README.md |
| 已解 bug 的 fix pattern | README.md（相關段落） |
| 零散技術筆記 | 必要時新建 `dev/tech-notes.md` |
| 架構決策 | 必要時新建 `dev/decisions/ADR-NNN-<kebab-name>.md` |
