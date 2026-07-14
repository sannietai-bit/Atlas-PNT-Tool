# ATLAS PNT 製作工具 - GitHub Pages 發布說明

這個工具是純前端網頁，圖片只在使用者自己的瀏覽器內處理，不會上傳到 GitHub 或伺服器。

## 建議方式

使用 GitHub Pages 發布整個 `AtlasPNT_Offline_Tool` 資料夾。

## 需要上傳的檔案

- `index.html`
- `app.js`
- `style.css`
- `palette.js`
- `.nojekyll`

`GitHubPages_發布說明.md` 可以保留在 repository 裡當說明文件。

## 發布步驟

1. 登入你的私人 GitHub 帳號。
2. 建立一個新的 repository，例如：`atlas-pnt-tool`。
3. 將本資料夾內的檔案上傳到 repository 根目錄。
4. 進入 repository 的 `Settings`。
5. 左側選擇 `Pages`。
6. `Build and deployment` 選擇 `Deploy from a branch`。
7. Branch 選 `main`，資料夾選 `/root`，按 `Save`。
8. 等待 1 到 3 分鐘，GitHub Pages 會產生網址。

網址通常會長這樣：

```text
https://你的帳號.github.io/atlas-pnt-tool/
```

## 更新方式

以後只要修改後重新上傳這幾個檔案，GitHub Pages 會自動更新。

## 小提醒

如果網頁更新後看起來還是舊版，請按 `Ctrl + F5` 強制重新整理。
