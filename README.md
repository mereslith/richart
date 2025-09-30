# Richart 單筆回饋計算工具

這是一個方便查詢 **Richart 卡單筆回饋（無條件捨去）** 的小工具，包含：
- 📊 Google 試算表線上版（可一鍵複製）
- 📑 Excel 範例檔（離線使用）
- 🌐 GitHub Pages 網頁版（手機/電腦直接打開就能算）

## 連結
- Google 試算表（可一鍵複製）：https://docs.google.com/spreadsheets/d/1JCUK8qSB6RIXIhHeOmsN6HCgQtJCoYUBXaJpGkCEV4X0/copy

## 使用
- 將 `index.html` 放到 GitHub repo 的 `docs/` 目錄，開啟 **Settings → Pages**，選 `main` + `docs/` 即可發布。
- Excel 範例檔：`Richart_回饋計算_範例檔.xlsx`，可直接開啟或上傳到 Google Drive 使用。

## 公式
- 回饋金額 = `ROUNDDOWN(金額 × 回饋率, 0)`
- 最低門檻 = `CEILING(N / 回饋率, 1)`
