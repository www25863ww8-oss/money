# 片場帳本

短影音接案工作室的每月客戶營收、外包支出與收支總覽，透過 Firebase Realtime Database 做跨裝置即時同步。

## 部署

這個 repo 接上 Netlify 後會自動部署 `index.html`（純靜態網站，無需 build 指令）。

## 資料

資料存放在 Firebase Realtime Database，與這個 repo（網頁外觀/程式邏輯）完全分開，重新部署不會影響已存的資料。
