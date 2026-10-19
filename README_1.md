# site-safety-photo-report

RBH-3-S05-02「工地交通安衛環保檢查彙整表（扣減通知單）」照片自動編排工具。

在瀏覽器裡逐筆填寫缺失、改善內容並上傳照片，一鍵產生格式與官方表單一致的 Word 檔（.docx）。

**線上使用：** `https://<你的GitHub帳號>.github.io/site-safety-photo-report/`

## 特色

- 純前端、單一 HTML 檔：照片與文字只在使用者自己的瀏覽器處理，不會上傳到任何伺服器（GitHub 只提供網頁本身）。
- 頁首可選「交通部鐵道局 北部／中部／南部 工程分局」（瀏覽器會記住上次選擇）。
- 檢查日期預設今天，可用日曆點選，自動轉為民國年格式（例：115年10月19日）。
- 會同人員可依單位分行，例如：
  ```
  工事科：王ＯＯ、李ＸＸ
  監造單位：李ＯＯ
  ```
- 手機介面：每個照片欄有「選相片／相機APP」（系統選單，可選相簿或其他相機 APP）與「直接拍照」（預設相機）。
- 每頁固定 2 筆檢查項目；照片自動縮放（橫向 9×6.75 cm、直向 6.5×4.87 cm）。
- 可匯出／匯入填寫進度（.json，含照片），也可上傳新版官方 Word 範本替換文字。

## 部署到 GitHub Pages

1. 在 GitHub 建立公開 repository：`site-safety-photo-report`
2. 上傳 `index.html` 與 `README.md`
3. Settings → Pages → Source 選 **Deploy from a branch**，Branch 選 `main`、資料夾 `/ (root)` → Save
4. 約 1 分鐘後即可用 `https://<帳號>.github.io/site-safety-photo-report/` 開啟

## 手機拍照說明

| 平台 | 「選相片／相機APP」 | 「直接拍照」 |
|---|---|---|
| Android | 系統選單：相機、相簿、檔案；部分機型可直接選已安裝的其他相機 APP | 開啟預設相機 |
| iPhone | 「照片圖庫／拍照／選擇檔案」 | 開啟內建相機 |

iPhone 無法從網頁直接叫用第三方相機 APP（例如工程水印相機），請先用該 APP 拍照存到相簿，再用「選相片」挑選。

## 製作

中工分局 鄭斯仲
