# 我的網頁作品集 | Grace Liu 呂逸庭 (MyWorks Portfolio)

> **Mobile-First Portfolio · 20 年產品開發經驗 × iPAS AI 應用規劃師**  
> *"Technology with Empathy — 從女性身型洞察到數位產品落地，創造有溫度且精準落地的科技產品。"*

本專案為 **Grace Liu 呂逸庭** 的個人前端互動網頁作品集（`MyWorks`），結合 20 年產品開發洞察與生成式 AI 輔助開發，運用 HTML5、Tailwind CSS、Canvas 2D、Web Audio API 與多項前端技術，打造 **12 件 100% RWD 手機優先適配的互動式網頁作品**，涵蓋專注計時、休閒遊戲、開運占卜、商務數位工具與個人品牌網站五大主題。

---

## ✨ 專案特色

- 📱 **Mobile-First 響應式設計**：針對手機、平板與桌面瀏覽器深度優化，內建手機專屬底部導覽列與橫向滑動分類篩選。
- 🌓 **深淺色主題切換（Dark / Light Mode）**：支援系統主題感知與 `localStorage` 偏好記憶，大地文藝配色溫潤護眼。
- 🔍 **即時分類篩選與關鍵字搜尋**：可依五大主題分類快速切換，或搜尋作品名稱、使用到的 Web API 及應用場景。
- 🖥️ **頁內即時互動預覽（In-Page Modal Preview）**：無須離開主頁即可在彈出視窗內直接體驗任一作品，亦支援新分頁獨立開啟。

---

## 📂 作品總覽（共 12 件互動作品）

### ⏱️ `clock/` 時鐘與專注計時（4 件）

| 編號 | 作品名稱 | 檔案路徑 | 核心技術與 API | 簡介與應用場景 |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **任務代號：解除拖延炸彈** | [`clock/clock_ count_code_artifact.html`](./clock/clock_%20count_code_artifact.html) | Tone.js 音訊合成、Web Audio BPM 動態調速、CSS 震動特效 | 特務拆彈主題遊戲化倒數計時器，隨時間減少動態加速心跳配樂與導火線燃燒，適合限時挑戰與擊退拖延症。 |
| **02** | **Grace 的美學計時器** | [`clock/clock_aesthetic_timer.html`](./clock/clock_aesthetic_timer.html) | localStorage、Canvas Confetti、SVG 圓環動畫、影像預載 | 融合吉卜利休閒、現代時尚與古典復古三主題的沉浸式計時器，支援自訂桌布輪播與正能量金句，適合冥想與伴讀。 |
| **03** | **超大型可愛動物時鐘** | [`clock/clock_large_cute_animal.html`](./clock/clock_large_cute_animal.html) | Fullscreen API、雙圖層 Cross-fade 緩存、Unsplash 影像 | 精選 12 張高解析度萌寵攝影全螢幕療癒時鐘，依時段自動切換暖心問候語，支援 12/24 小時制與調光。 |
| **04** | **航海王熱血大數字倒數計時器** | [`clock/clock_one piece_artifact.html`](./clock/clock_one%20piece_artifact.html) | Web Audio 原生音效合成、Fullscreen API、Document Title 同步 | 三大航海主題漸層配色與橡膠彈跳手感，內建原生合成勝利號角與彩帶特效，適合 25 分鐘番茄鐘與團康倒數。 |

### 🎮 `game/` 互動休閒遊戲（2 件）

| 編號 | 作品名稱 | 檔案路徑 | 核心技術與 API | 簡介與應用場景 |
| :--- | :--- | :--- | :--- | :--- |
| **05** | **星際航擊大作戰 Galaxy Striker** | [`game/game_ Galaxy Striker.html`](./game/game_%20Galaxy%20Striker.html) | HTML5 Canvas 2D、Web Audio 138 BPM 編曲合成器、Touch Events | 具備三層視差滾動星空的街機風縱向太空射擊遊戲，支援多波次敵機、Boss 戰、連擊系統與多種武裝道具掉落。 |
| **06** | **《打磚塊大作戰》— 賽博航海篇** | [`game/game_brick_artifact.html`](./game/game_brick_artifact.html) | HTML5 Canvas 2D 物理與粒子、Web Audio BiquadFilter 合成 | 結合賽博龐克霓虹視覺與四大強化惡魔果實（分身、變寬、武裝色貫穿、霸王色防護網）的物理粒子打磚塊遊戲。 |

### 🔮 `Lucky/` 開運選號與占卜（3 件）

| 編號 | 作品名稱 | 檔案路徑 | 核心技術與 API | 簡介與應用場景 |
| :--- | :--- | :--- | :--- | :--- |
| **07** | **十二星座週運速報** | [`Lucky/star sign.html`](./Lucky/star%20sign.html) | CSS `light-dark()`、ARIA 無障礙狀態連動、新野獸派版面 | 美式復古報刊與新野獸派風格星座週運指南，呈現整體節奏、幸運指數、幸運色/數字及愛情、工作、財運解析。 |
| **08** | **喵嗚萌萌大樂透．開運隨機選號機** | [`Lucky/taiwan_lotto_lucky_picker.html`](./Lucky/taiwan_lotto_lucky_picker.html) | Tone.js PolySynth 音效、Clipboard API、加權與奇偶平衡演算法 | 結合招財貓歐氣互動的台灣大樂透（01~49 選 6 碼）選號工具，提供四大選號演算法、必含/排除號碼與五組連發包牌。 |
| **09** | **月影塔羅 Moonlit Tarot** | [`Lucky/Tarot cards.html`](./Lucky/Tarot%20cards.html) | 78 張偉特塔羅資料集、CSS 3D 翻牌特效、動態 SVG 牌面繪製 | 羊皮紙與夜藍金箔美學三牌陣（過去、現在、未來）占卜系統，收錄完整 78 張正逆位中文牌義與五大提問方向總結。 |

### 💼 `others/` 商務與生活工具（2 件）

| 編號 | 作品名稱 | 檔案路徑 | 核心技術與 API | 簡介與應用場景 |
| :--- | :--- | :--- | :--- | :--- |
| **10** | **企業差旅費報支申請系統** | [`others/business travel expence claim code_artifact.html`](./others/business%20travel%20expence%20claim%20code_artifact.html) | ExcelJS 報表格式化匯出、FileSaver.js / Blob 下載、動態表單 | 支援多幣別（TWD、USD、JPY 等）與八大費用類別動態試算，可一鍵匯出含專業框線與簽核欄位的 `.xlsx` 報表。 |
| **11** | **招財喵吉發票對獎機** | [`others/invoice code_artifact.html`](./others/invoice%20code_artifact.html) | Html5Qrcode 相機與圖片掃碼、MediaDevices 鏡頭、Web Audio | 整合「眼睛直覺看板」、「末三碼九宮格快篩」、「完整 8 碼比對」與「相機 QR Code 掃碼」四合一統一發票對獎神器。 |

### 👩‍💼 `about/` 個人品牌與 AI 諮詢（1 件）

| 編號 | 作品名稱 | 檔案路徑 | 核心技術與 API | 簡介與應用場景 |
| :--- | :--- | :--- | :--- | :--- |
| **12** | **Grace Liu 個人品牌與 AI 諮詢網站** | [`about/portfolio_website.html`](./about/portfolio_website.html) | Fetch API + Google Apps Script、Schema.org JSON-LD (AEO) | 展現 20 年服飾開發顧問百萬件銷售實績與 AI PM 轉型願景，內建背景音樂播放器、AEO 結構化標記與線上預約諮詢表單。 |

---

## 🗂️ 專案目錄結構

```text
MyWorks/
├── index.html                                                # 作品集總覽主頁（含分類篩選、搜尋、頁內預覽 Modal）
├── README.md                                                 # 專案說明文件
├── about/
│   ├── portfolio_website.html                                # 12. Grace Liu 個人品牌與 AI 諮詢網站
│   ├── 內衣開發者的AI跨界之路.png                             # 跨界歷程視覺圖卡
│   └── 產品專家的跨界數據思維.png                             # 數據思維視覺圖卡
├── clock/
│   ├── clock_ count_code_artifact.html                       # 01. 任務代號：解除拖延炸彈
│   ├── clock_aesthetic_timer.html                            # 02. Grace 的美學計時器
│   ├── clock_large_cute_animal.html                          # 03. 超大型可愛動物時鐘
│   └── clock_one piece_artifact.html                         # 04. 航海王熱血大數字倒數計時器
├── game/
│   ├── game_ Galaxy Striker.html                             # 05. 星際航擊大作戰 Galaxy Striker
│   ├── game_ Galaxy Striker.docx                             # 星際航擊大作戰設計說明文件
│   └── game_brick_artifact.html                              # 06. 《打磚塊大作戰》— 賽博航海篇
├── Lucky/
│   ├── star sign.html                                        # 07. 十二星座週運速報
│   ├── taiwan_lotto_lucky_picker.html                        # 08. 喵嗚萌萌大樂透．開運隨機選號機
│   └── Tarot cards.html                                      # 09. 月影塔羅 Moonlit Tarot
├── others/
│   ├── business travel expence claim code_artifact.html      # 10. 企業差旅費報支申請系統
│   └── invoice code_artifact.html                            # 11. 招財喵吉發票對獎機
└── assets/                                                   # 專案靜態圖片與視覺素材
```

---

## 🚀 如何瀏覽與使用

1. **本地直接開啟**：下載或 Clone 本專案後，直接使用瀏覽器開啟根目錄下的 [`index.html`](./index.html)，即可瀏覽完整 12 件作品目錄並進行互動體驗。
2. **GitHub Pages 線上瀏覽**：若已啟用 GitHub Pages，可直接透過 `https://graceliu0508.github.io/MyWorks/` 線上訪問。

---

## 👩‍💼 關於作者 | Grace Liu 呂逸庭

- **背景經歷**：20 年女性服飾與內衣產品開發、採購管理經驗，主導開發之舒適內衣累計突破 **1,000,000+ 百萬件** 銷售佳績。
- **專業認證**：經濟部 **iPAS AI 應用規劃師** 初級認證。
- **核心哲學**：**洞察與傾聽 → 親身驗證 → 落地量產**，將 20 年產品思維結合生成式 AI 與前端互動技術，轉化為 AI PM 的核心動能。
- **社群連結**：
  - 🔗 [LinkedIn (@graceliu0508)](https://www.linkedin.com/in/graceliu0508)
  - 🔗 [Facebook](https://www.facebook.com/grace.liu.79219)
