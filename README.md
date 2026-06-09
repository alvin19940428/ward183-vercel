# 183病房物品點班系統 - Vercel版

這是將 Gemini Canvas 產出的 React 介面整理成 Vite + React 專案後，可直接部署至 Vercel 的版本。

## 本機執行

```bash
npm install
npm run dev
```

## Vercel 部署

1. 將整個專案推到 GitHub。
2. 在 Vercel 選擇 Import Project。
3. Framework Preset 選 Vite。
4. Build Command 使用 `npm run build`。
5. Output Directory 使用 `dist`。
6. 在 Environment Variables 加入 `.env.example` 內的 Firebase 變數。

## Firebase

若沒有設定 Firebase 環境變數，系統會自動以瀏覽器 localStorage 單機模式運作。

若要雲端同步，請在 Firebase Console：

1. 建立 Web App。
2. 啟用 Authentication 的 Anonymous 匿名登入。
3. 建立 Cloud Firestore。
4. 設定 Firestore Security Rules。
