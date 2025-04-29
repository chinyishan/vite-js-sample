# 【sample】Vue3 + Vite 樣板

## 專案簡介
此專案建立了基礎的 Vue 3 + Vite 開發環境，整合常用的開發工具與套件，並預設了常見的資料夾結構與共用模組。
目的是統一開發基底，提升新專案建立的效率與一致性，避免重複設定，加速開發流程。

## 使用技術與工具
- Vue 3：前端框架（使用 Composition API）
- Vite：開發與建構工具
- Pinia：狀態管理
- Vue Router 4：路由管理
- SCSS：樣式撰寫與響應式設計
- Axios：API 請求處理
- ESLint + Prettier：代碼格式與規範
- 環境變數設定 (.env)：管理 API 路徑、設定參數
- Vite Plugin Auto Import（可選）：自動引入常用 API（如 ref、reactive）

## 專案結構概覽 
```
src/
  ├── assets/        # 樣式、圖片等靜態資源
  ├── components/    # 可重用的 UI 元件
  ├── pages/         # 頁面模組（對應路由）
  ├── stores/        # Pinia 狀態管理
  ├── router/        # Vue Router 設定
  ├── utils/         # 公用工具函式
  ├── services/      # API 請求封裝
  ├── composables/   # 自訂 hooks（可選）
  └── plugins/       # 插件設定（如 axios、i18n 等）
```

## 使用方式
```
git clone <你的倉庫網址>
cd <專案資料夾>
npm install
npm run dev
```
