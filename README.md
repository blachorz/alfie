# Alfie

## 圖文指南

- [GitHub × Cloudflare × D1：從程式碼到上線](docs/cloudflare-github-d1/index.html)

網頁原始檔位於 `docs/`，使用純 HTML、CSS 與內嵌 SVG，不需要 npm 安裝或建置。

| 路徑 | 用途 |
| --- | --- |
| `docs/index.html` | 網站入口 |
| `docs/cloudflare-github-d1/index.html` | Cloudflare 與 D1 圖文指南 |
| `docs/.nojekyll` | 使用 GitHub Pages 時直接發布靜態檔案 |

## 發布設定

### GitHub Pages

在儲存庫 **Settings → Pages** 選擇：

- Source：**Deploy from a branch**
- Branch：**main**
- Folder：**/docs**

以 Pages 實際回傳的網站網址為準；指南的獨立路徑為 `cloudflare-github-d1/`。私有個人儲存庫需具備支援 private-repo Pages 的 GitHub 方案。

### Cloudflare Pages

如使用 Cloudflare Pages 連接此儲存庫：

- 正式分支：`main`
- Framework preset：`None`
- Build command：留空
- Build output directory：`docs`

網站發布後，指南可由網站網址下的 `/cloudflare-github-d1/` 開啟。

## 更新指南

修改 `docs/cloudflare-github-d1/index.html` 並提交到 `main`，已接通的 Git 部署流程即可發布新版本。圖表設計來源與 MIT 授權保留在指南 HTML 中。
