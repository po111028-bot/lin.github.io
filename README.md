🍃 Minimalist Journey Planner | 日系極簡風行程規劃器

這是一個單頁式（Single-Page Application, SPA）的旅遊行程規劃應用程式介面，採用 日系極簡美學 設計，配色以柔和的湖水綠（Teal/Emerald）為主色調，旨在提供如手機 App 般流暢的使用體驗。

🛠️ 技術棧

前端框架: Vue.js 3 (CDN 版本)

CSS 框架: Tailwind CSS (CDN 版本)

單檔案架構: 所有 HTML, CSS, JavaScript 程式碼都包含在單一 index.html 文件中，方便部署於 GitHub Pages 或任何靜態伺服器。

✨ 主要特色

日系極簡風格 (Minimalist Aesthetic): * 採用簡潔的卡片式設計、圓角和淡色背景，視覺效果舒適且現代。

主色調為湖水綠 (Teal)，營造清新感。

手機 App 體驗:

橫向滑動日期選單: 模擬手機應用程式的日期選擇器，方便切換每日行程。

完全響應式 (Fully Responsive): 介面在手機和桌面上都能良好顯示。

行程管理 (CRUD):

新增、編輯、刪除 (Add, Edit, Delete): 可針對每日行程進行時間、地點、細節和預計費用的管理。

時間排序: 新增或編輯後，行程會自動依時間排序。

整合資訊:

天氣資訊: 模擬自動抓取行程地點的當地氣溫與天氣狀況，顯示在頂部卡片上。

地圖與導航: 點擊行程卡片上的「導航」按鈕，即可快速開啟 Google Maps 進行路線規劃。

🚀 如何啟動

由於程式碼完全包含在 index.html 中，啟動方式非常簡單：

克隆或下載本 Repository。

用瀏覽器打開 index.html 檔案。 (推薦使用 Chrome, Firefox 等現代瀏覽器)

部署到 GitHub Pages

將此 index.html 檔案上傳到您的 GitHub Repository 根目錄。在 Repository 設定中啟用 GitHub Pages，並選擇 main 分支作為來源即可立即部署。

⚠️ 注意事項

天氣功能為模擬: 程式碼中的 fetchWeather 函數目前僅返回模擬的靜態天氣數據。若要在實際應用中使用，請參閱程式碼中的註釋，將其替換為您自己的天氣 API 呼叫（例如 OpenWeatherMap）。

數據非持久化: 由於此為單頁靜態應用，行程數據僅存在於瀏覽器記憶體中。刷新頁面後，所有變更將會遺失。若需要持久化儲存，建議整合如 Firebase Firestore 或 LocalStorage 儲存機制。
