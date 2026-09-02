# NTTU CSIE 大二讀書規劃 & CPE 突破 Dashboard 🎓

> **專為國立臺東大學資訊工程學系大二學生打造的個人化學習導航系統**  
> 核心戰略：**維持推甄系排優勢 (Top 10%~15%) × CPE 從 0 題漸進突破 × 嵌入式/AI硬體長期方向**

![Dashboard Preview](https://img.shields.io/badge/NTTU-CSIE%20115--1-blue?style=for-the-badge&logo=googlescholar)
![CPE](https://img.shields.io/badge/CPE-0%20%E2%86%92%20Lv.6%20Roadmap-emerald?style=for-the-badge&logo=cplusplus)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge)

---

## 🌟 核心特色 (Key Features)

### 1. ⏱️ 今日智慧時間分配器 (Dynamic Time Allocator)
- 真正解決：**「今天只有 2～3 小時，我到底最該讀哪一科、讀多久、具體做什麼動作？」**
- 考量「推甄必修權重 × 考試倒數天數 × 當前掌握漏洞 × CPE 漸進目標 × 當前精力狀態」，精確計算到分鐘的行動清單。

### 2. 📅 官方真實週課表與每日可持續模板 (Timetable & Weekly Template)
- 完整收錄 115-1 校務系統 9 門課程（24 學分）彩色列印與時段標籤。
- 星期一至星期日提供 **【最低完成量】**、**【標準完成量】** 與 **【有空加碼】**，拒絕塞滿式排程，保留生活彈性。

### 3. 🧠 9 大課程深度剖析與跨領域知識地圖 (Course Deep-Dive & Knowledge Map)
- 逐科白話詳解、重要程度四級分類（🔴/🟠/🟡/🟢）。
- 八大維度實戰指引（預習/複習節奏/必背/必懂/必做/常見失分原因/驗證學會標準）。
- 貫通【離散 ↔ 演算法 ↔ CPE】與【組語 ↔ 數位系統 ↔ 嵌入式 ↔ AI硬體】之知識脈絡。

### 4. 💻 CPE 0 題漸進升級專屬系統 (From 0 AC to Mastery)
- **拒絕盲目刷題**：建立 **Lv.0 ~ Lv.6 六大能力等級** 與 **Stage 0 ~ Stage 3** 學習路線圖。
- **6 步驟刻意練習循環法**：自己嘗試 ➔ 卡住深度分析 ➔ 看思路提示 ➔ 關閉答案重寫 ➔ 記錄錯題本 ➔ 3天後間隔重測。
- **即時練習記錄器 & 錯題本**：追蹤花費時間、AC/WA、踩坑筆記與題型弱項雷達。
- **動態週時數調整**：考試週 2-3h、一般週 4-6h、輕鬆週 6-8h。

### 5. 🎯 考試五階段備戰系統 (5-Phase Exam Countdown)
- 嚴謹 14 天階段遞進備戰模型（考前14~10天確認範圍 ➔ 9~6天大量做題 ➔ 5~3天補弱點 ➔ 2天全真模擬 ➔ 1天輕量睡眠）。
- 即時掌握度滑桿與一鍵生成考前衝刺任務。

### 6. 📈 各科健康診斷與智慧時間移轉 (Course Health Monitor)
- 🟢 穩定 | 🟡 注意 | 🔴 危險
- 若通識科目亮綠燈，系統自動壓縮通識時數至 0~15 分鐘，將時間自動移轉給高風險專業科目或 CPE。

### 7. 📝 每週覆盤 (Weekly Review) & 專注番茄鐘
- 每週日自評問卷，自動生成下週時間重分配戰略。
- 內建 25m / 45m / 60m 深度學習專注計時器。
- 本地 LocalStorage 資料自動保存與 JSON 備份匯出。

---

## 🚀 快速開始與本地預覽 (Getting Started)

本專案為純前端單頁應用（SPA），無需複雜的 Node.js 編譯流程，支援 GitHub Pages 免費靜態託管：

1. **直接開啟：**
   雙擊 `index.html` 即可在任一現代瀏覽器中流暢運行。

2. **使用 VS Code Live Server 預覽：**
   安裝 Live Server 套件後，右鍵點擊 `index.html` 選擇 `Open with Live Server`。

---

## 🌐 部署至 GitHub Pages 步驟

1. 在 GitHub 上建立一個新的公開或私有 Repository（例如 `nttu-csie-study-dashboard`）。
2. 在終端機執行以下指令推送代碼：
   ```bash
   git init
   git add .
   git commit -m "feat: Initial commit of NTTU CSIE Study Dashboard"
   git branch -M main
   git remote add origin https://github.com/<你的GitHub帳號>/nttu-csie-study-dashboard.git
   git push -u origin main
   ```
3. 進入 GitHub Repository 的 **Settings ➔ Pages**，在 Branch 選擇 `main` / `root` 並儲存，即可獲得專屬線上儀表板網址！

---

## 📋 課程資料來源與版權說明 (Attribution)

- 課表與課程大綱依據國立臺東大學校務系統 115 學年度第 1 學期正式選課紀錄分析製作。
- 遵循學術研究與個人化學習輔助用途。

---

*Made with 💙 for NTTU CSIE Students.*
