# Kevin Lin — Data Portfolio

一個精美、現代且功能完整的**個人資料作品集網站**，展示資料工程、MLOps 與深度學習等領域的端對端實作專案，並附有技術文章與技能清單。

## 🔗 線上展示 (Live Demo)
👉 **[點此進入 Live Demo](https://kevinlin13.github.io/L2-DIC-github/)**

## 📖 簡介

此作品集網站以求職為導向，目標受眾為資料產業的招募方與合作夥伴。網站採用純前端技術（HTML + React + TailwindCSS），無需後端即可部署，並透過 GitHub Pages 提供穩定的線上存取。

> 每一個專案都代表真正端對端的實作——真實的架構決策、真實的除錯過程、真實的技術文件。這是我用行動說話的方式。

## 🌟 網站特色 (Features)

- **多頁面 SPA 架構**：以 Hash Router 實現 Home / Projects / Articles 三個頁面的無刷新切換。
- **專案展示 (Projects)**：具備全文搜尋與分類篩選功能，目前涵蓋資料工程、MLOps、深度學習三大領域。
- **技術文章 (Articles)**：展示撰寫的技術文章，可依分類篩選與關鍵字搜尋。
- **技能清單 (Skills)**：以 Pill 標籤清晰呈現技術棧，涵蓋資料工程、ML/AI、Infrastructure 與程式語言。
- **響應式設計 (Responsive)**：完美支援手機、平板與桌上型電腦。
- **精緻動畫**：頁面切換動畫、卡片 Hover 效果與 Staggered Fade-up 進場動畫，提升使用體驗。
- **現代排版**：引入 Google Fonts 的 *Inter* 與 *Noto Sans TC*，呈現高品質中英文排版。

## 🛠️ 技術棧 (Tech Stack)

| 層面 | 技術 |
|------|------|
| 結構 | HTML5（語意化標籤） |
| 樣式 | TailwindCSS CDN + Vanilla CSS（客製化元件） |
| 邏輯 | React 18（透過 Babel Standalone 編譯，無需 Node.js） |
| 路由 | Hash-based Client-side Router |
| 字型 | Google Fonts — Inter、Noto Sans TC |
| 部署 | GitHub Pages |

## 📂 專案內容

### 🔧 Data Engineering
- **Automated Data Pipeline with Apache Airflow** — 端對端 ETL 協作系統，含 DAG 設計、Schema 驗證與自動重試機制。

### 🤖 MLOps
- **End-to-End MLOps Model Deployment Pipeline** — 以 MLflow 進行實驗追蹤，整合 CI/CD 自動部署與 Docker 容器化。

### 🧠 Deep Learning
- **PyTorch Time-Series Forecasting with SHAP Analysis** — 多變量時序預測模型，搭配 SHAP 解釋性分析與自訂 Attention 機制。

## 🚀 如何在本地運行 (How to Run Locally)

1. 複製此儲存庫：
   ```bash
   git clone https://github.com/KevinLin13/L2-DIC-github.git
   ```
2. 進入專案資料夾後，直接雙擊打開 `index.html` 即可在瀏覽器中預覽。
   > ⚠️ 由於使用 Babel Standalone 進行即時編譯，建議透過本地伺服器（如 VS Code Live Server）開啟以獲得最佳效能。

## 👤 作者 (Author)
* **林建璋 Kevin Lin** — [GitHub](https://github.com/KevinLin13)
