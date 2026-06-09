# 183病房物品點班系統

Vite + React + Tailwind CSS 版本，適合部署於 Vercel。

## v11 更新

- 新增「統計」頁籤。
- 新增月統計儀表板：本月紀錄、異常紀錄、常規未完成、有備註紀錄。
- 新增最常異常物品排行榜。
- 新增常見異常原因排行榜。
- 新增異常區域分布、班別分布、本月點班人員統計。
- 新增一鍵複製月統計摘要，可貼到 LINE 或交班群組。
- 保留 v10 交班摘要、v9 上一班提醒、v8 歷史紀錄篩選、v7 防重複與備註功能。
- 已維持專案結構乾淨，真正使用的檔案都放在 `src/` 下。

## 部署

```bash
npm install
npm run build
```

Vercel 設定：

- Framework Preset: Vite
- Build Command: npm run build
- Output Directory: dist

## 注意

目前可維持 localStorage 單機版使用。Firebase 設定可暫時不啟用。

## v12 更新：頭像記憶修正

- 修正使用者更換或上傳頭像後，關閉瀏覽器再開時頭像沒有記憶的問題。
- 將 `ward183_local_users` 正式寫入 localStorage。
- 登入時若輸入曾經登入過的姓名，會自動帶回已儲存的頭像。
- 保留 v11 月統計、v10 交班摘要、v9 上一班追蹤提醒、v8 篩選與 v7 防重複備註功能。
