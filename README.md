# 飲料店訂餐系統 (Beverage Ordering System)

🔗 [專案連結](https://williamhsieh615.github.io/beverage-ordering-system/)

## 專案簡介

本專案「飲料點餐系統」是一個基於 Vue.js (採用選項式 API) 和 Vite 打造的前端 Web 應用，使用 Bootstrap 5 作為 UI 框架。此系統用於提供使用者線上選購飲料的功能，介面友好且響應迅速。

## 功能特色

- 直觀點餐介面：展示飲料列表與價格，使用者可以輕鬆選擇飲品並加入購物車。界面更新時即時反映加入或刪除的項目，藉由 Vue 的雙向資料綁定（如 v-model）技術確保資訊同步更新。
- 購物車管理：購物車可顯示已選飲品清單、單價、數量與總價。使用者可調整商品數量或刪除品項，系統會即時計算總金額，保持資料一致。
- 響應式設計：採用 Bootstrap 5 的響應式佈局，自動調整不同螢幕尺寸的顯示效果，確保在桌機、平板及手機上都有良好閱讀與操作體驗。
- 現代化開發：運用 Vite 開發伺服器提供快速即時重載（HMR）功能，加速開發迭代；專案採單頁應用架構，使用者操作不需重新載入頁面。

## 技術棧

- **Vue 3 (Options API)**：進階、易學的前端框架，用於構建互動式使用者介面。
- **Vite**：下一代前端構建工具，由 Vue 的創作者開發，提供快速啟動與熱重載效能。
- **Bootstrap 5**：響應式 CSS 框架，提供各種排版與元件樣式。搭配 Bootstrap 的 JavaScript 插件 (Popper.js 等) 以支援下拉選單等功能。
- **Node.js & NPM**：需安裝 Node.js 執行環境，用於管理套件與運行開發伺服器。開發時使用 npm 安裝相依套件（如 Vue、Bootstrap 等）並執行指令。
- **其他工具**： 專案包含 ESLint、Prettier、EditorConfig 等設定檔，協助統一程式碼風格與開發流程。

## 安裝與執行

1. 先行安裝 Node.js (建議版本 16 以上)，以確保能運行 npm 套件和 Vite 。

2. clone 此專案到本機：
    ```bash
    git clone https://github.com/WilliamHsieh615/beverage-ordering-system.git
    cd beverage-ordering-system

3. 安裝相依套件：
    ```bash
    npm install

4. 啟動開發伺服器：
    ```bash
    npm run dev

  執行後，Vite 會在預設的 http://localhost:5173 啟動服務，您可以在瀏覽器中打開此網址，檢視點餐系統的即時效果。

5. 如需產生生產版本，可執行 npm run build，完成後輸出的檔案將放在 dist/ 資料夾。
  





