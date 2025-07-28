# Vite React GitHub Pages 部署模板

這是一個使用 Vite + React 的專案模板，配置了自動化部署到 GitHub Pages 的工作流程。透過 GitHub Actions，當您推送程式碼時，網站會自動部署到 GitHub Pages。

## 功能特點

- ⚡️ 使用 Vite 作為建置工具
- ⚛️ React 18+ 開發環境
- 🔄 自動化 GitHub Actions 部署流程

## 快速開始

1. 使用這個模板創建新的儲存庫
2. 克隆您的儲存庫到本地
   ```bash
   git clone https://github.com/您的使用者名稱/您的儲存庫名稱.git
   ```
3. 安裝依賴
   ```bash
   npm install
   ```
4. 本地開發
   ```bash
   npm run dev
   ```

## 部署設定

1. 在您的 GitHub 儲存庫中啟用 GitHub Pages：
   - 前往儲存庫設定 (Settings)
   - 選擇 Pages 選項
   - 在 "Build and deployment" 區域選擇 "GitHub Actions"

2. 推送程式碼到 master 分支：
   ```bash
   git add .
   git commit -m "您的提交訊息"
   git push origin master
   ```

3. GitHub Actions 會自動執行部署流程，您可以在儲存庫的 Actions 頁面查看進度。

## 專案結構

```
/
├── src/             # 源碼目錄
├── public/          # 靜態資源
├── .github/         # GitHub Actions 設定
│   └── workflows/   # 工作流程設定
├── vite.config.js   # Vite 設定
└── package.json     # 專案配置
```

## 開發指令

- `npm run dev` - 啟動開發伺服器
- `npm run build` - 建置生產版本
- `npm run preview` - 預覽生產版本
- `npm run lint` - 執行程式碼檢查

## 技術支援

如果您在使用此模板時遇到任何問題，歡迎在 Issues 中提出。
