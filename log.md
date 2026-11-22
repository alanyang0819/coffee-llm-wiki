# Log

append-only 操作紀錄。新 entry 加在檔案末端。

## [2026-11-22] ingest | Coffee Cultivation
- 來源：`raw/sources/咖啡栽培.pdf`
- 摘要：萃取並建立咖啡栽培來源頁，涵蓋主要品種、氣候土壤、繁殖定植、整枝更新與施肥管理。
- 新增頁面：`wiki/process/coffee-cultivation.md`、`wiki/entities/coffee-species.md`、`wiki/concepts/coffee-climate-soil.md`、`wiki/concepts/coffee-propagation.md`、`wiki/concepts/coffee-pruning.md`、`wiki/concepts/coffee-fertilization.md`、`wiki/sources/coffee-cultivation-tbrs.md`
- 更新頁面：`wiki/overview/main.md`、`index.md`
- 衝突／待確認：
  - 市場 70/30 比例未提供統計年代、地理範圍或口徑，保留為來源陳述並標示待核實。
  - 來源無明確出版日期，未將列印日期視為出版日期。

## [2026-11-22] ingest | Coffee Processing
- 來源：`raw/sources/咖啡加工處理.pdf`
- 摘要：萃取並建立咖啡採收後的日曬、水洗與半水洗處理頁，包含流程、用水差異、風味敘述與黴菌風險。
- 新增頁面：`wiki/process/coffee-processing.md`、`wiki/concepts/natural-process.md`、`wiki/concepts/washed-process.md`、`wiki/concepts/semi-washed-process.md`、`wiki/sources/coffee-processing-tbrs.md`
- 更新頁面：`wiki/process/coffee-cultivation.md`、`index.md`
- 衝突／待確認：
  - 「水洗法較柔順」與產地案例未提供感官控制、地理與年代範圍，保留為來源敘述而不擴寫為因果結論。
  - 半水洗法的實作定義因地區而異，本頁暫依來源的「去除部分膠質後直接乾燥」定義。

## [2026-11-22] ingest | Coffee Roasting
- 來源：`raw/sources/咖啡烘焙.pdf`
- 摘要：萃取並建立烘焙流程、烘焙階段、烘焙度與烘焙機導熱方式頁，包含失重、體積膨脹、冷卻及爆裂現象。
- 新增頁面：`wiki/process/coffee-roasting.md`、`wiki/concepts/roasting-phases.md`、`wiki/concepts/roast-levels.md`、`wiki/concepts/roaster-types.md`、`wiki/sources/coffee-roasting-tbrs.md`
- 更新頁面：`wiki/process/coffee-processing.md`、`index.md`
- 衝突／待確認：
  - 爐溫、豆溫、設備校正與批次量未提供，烘焙數值僅標示為來源描述，不建立成通用曲線。
  - 來源烘焙度分類依爆裂、油光與煙氣描述，未建立跨機器完全等值的時間標準。

## [2026-11-22] ingest | Coffee Brewing
- 來源：`raw/sources/咖啡沖泡.pdf`
- 摘要：萃取並建立沖泡流程、研磨粗細、萃取變因與主要沖泡方法頁，包含義式參數及賽風、摩卡、過濾等原理。
- 新增頁面：`wiki/process/coffee-brewing.md`、`wiki/concepts/coffee-grind-size.md`、`wiki/concepts/coffee-extraction-variables.md`、`wiki/concepts/brewing-methods.md`、`wiki/sources/coffee-brewing-tbrs.md`
- 更新頁面：`wiki/process/coffee-roasting.md`、`index.md`
- 衝突／待確認：
  - 文內「研磨愈細／粗」與烘焙度調整為方向性規則，尚缺粉水比、萃取率、TDS 與感官控制條件。
  - 義式 90.5–96°C、8.5–9.5 bar、20–30 秒為來源概述，未補齊粉量、萃取液重與機器前提。

## [2026-11-22] ingest | Coffee Roasting Curve
- 來源：`raw/sources/咖啡豆烘焙時間及溫度曲線初探分享.pdf`
- 摘要：萃取並建立烘焙曲線重複性、A/B/C 階段案例、設備變因、風味校正及六種豆模式。
- 新增頁面：`wiki/sources/roasting-curve-forestry-tfri.md`、`wiki/concepts/roasting-reproducibility.md`、`wiki/concepts/roasting-troubleshooting.md`
- 更新頁面：`wiki/concepts/roasting-phases.md`、`index.md`
- 衝突／待確認：
  - A/B/C、火力、風門與鍋爐轉速數值來自楊家 800N 特定機型與案例，不得視為通用配方。
  - 文件為初探分享與經驗調整，六種豆模式保留為案例，需核對原始圖表及完整方法。

## [2026-11-22] ingest | Coffee Cupping
- 來源：`raw/sources/咖啡杯測.pdf`
- 摘要：萃取並建立杯測目的、環境與設備、烘焙沖煮準備、乾濕香及八項感官評估頁。
- 新增頁面：`wiki/process/coffee-cupping.md`、`wiki/concepts/cupping-protocol.md`、`wiki/concepts/cupping-sensory-attributes.md`、`wiki/sources/coffee-cupping-tbrs.md`
- 更新頁面：`wiki/process/coffee-brewing.md`、`index.md`
- 衝突／待確認：
  - 來源圖表中的 SCAA 與 CoE 評分表未以文字完整擷取，暫保留為待補欄位。
  - 1:19–1:21、Agtron #55–#65、8–12 分鐘與 93°C 為來源程序參數，尚缺盲測、杯數與完整標準細節。

## [2026-11-22] ingest | Coffee Postharvest Classification
- 來源：`raw/sources/咖啡後製分類.pdf`
- 摘要：萃取並建立三種後製分類、成熟度篩選、乾燥含水率、缺陷風險及黑/紅/黃/白蜜分類頁。
- 新增頁面：`wiki/concepts/honey-process.md`、`wiki/sources/coffee-postharvest-classification-moaq.md`
- 更新頁面：`wiki/concepts/natural-process.md`、`wiki/concepts/washed-process.md`、`wiki/concepts/semi-washed-process.md`、`index.md`
- 衝突／待確認：
  - 100 公斤果實得約 20 公斤生豆僅為概略產出率。
  - 蜜處理黑/紅/黃/白色與果肉留存比例在來源中未給精確數值，保留為相對分類。

## [2026-11-22] ingest | Taiwan Coffee Flavor Wheel
- 來源：`raw/sources/臺灣咖啡風味輪介紹.pdf`
- 摘要：建立臺灣風味輪與三大感官、七類調性及 TCAGs 數位評鑑連接。
- 新增頁面：`wiki/concepts/taiwan-coffee-flavor-wheel.md`、`wiki/sources/taiwan-coffee-flavor-wheel-tbrs.md`
- 更新頁面：`wiki/concepts/cupping-sensory-attributes.md`、`index.md`
- 衝突／待確認：
  - 來源未提供完整風味輪內圈詞彙與分項定義，未自行補寫細項。

## [2026-11-22] ingest | TCAGs
- 來源：`raw/sources/臺灣咖啡分類分級系統(TCAGs)簡介.pdf`
- 摘要：建立 TCAGs 評鑑、風味輪、智慧挑豆、溯源、特選精選優選與產業定位頁。
- 新增頁面：`wiki/concepts/tcags.md`、`wiki/sources/tcags-tbrs.md`
- 更新頁面：`wiki/concepts/taiwan-coffee-flavor-wheel.md`、`index.md`
- 衝突／待確認：
  - 特選、精選、優選的分數閾值與完整評分欄位未在來源中列出。
  - 智慧挑豆機準確度、瑕疵類別與權重尚未由來源證實。

## [2026-11-22] ingest | Taiwan Coffee History
- 來源：`raw/sources/臺灣咖啡簡史.pdf`
- 摘要：建立臺灣咖啡傳入說法、日治試種、銹病衝擊、戰後復甦、現代消費與精品化頁。
- 新增頁面：`wiki/entities/taiwan-coffee-history.md`、`wiki/sources/taiwan-coffee-history-tbrs.md`
- 更新頁面：`wiki/concepts/coffee-climate-soil.md`、`index.md`
- 衝突／待確認：
  - 傳入年份保留 1881 與 1884 兩種文獻說法。
  - 歷史面積與產量來自不同时期統計口徑，未視為同一基準序列。

## [2026-11-22] lint | Initial Wiki Baseline
- 原始來源：10 篇 PDF
- 來源頁：10 頁
- Wiki 頁：38 頁
- 連結檢查：無斷鏈
- 孤兒頁檢查：無孤兒頁
- 基線確認：使用者確認保留目前結構

## [2026-11-22] style | Hand-drawn Slide Redesign
- 修改：`outputs/coffee-from-seed-to-cup.html`
- 規格：米白紙感、深咖啡文字、焦糖重點、手繪 SVG 線條、流程箭頭、親切標題字型與充足留白。
- 範圍：保留 13 頁與既有內容架構；移除投影片對外部圖片資產的依賴。
- 操作：保留鍵盤、觸控、滑鼠翻頁及列印。

## [2026-11-22] update | Assets Restored in Slides
- 更新：投影片主要視覺區恢復使用 `raw/assets/` 圖片。
- 使用圖資：咖啡果實、處理法比較、烘焙曲線與手沖步驟。
- 保留：手繪框線、流程箭頭、焦糖標記、標題與留白版式。

## [2026-11-22] output | Slide Production Workflow Graph
- 產出：`outputs/slide-production-workflow.mmd`
- 格式：Mermaid flowchart
- 範圍：需求、內容、腳本、視覺、驗證與交付的端到端製作流程。
- 特點：包含需求、大綱、逐頁腳本、視覺設計與最終交付確認閘門，以及失敗或資產缺失時的回饋分支。

## [2026-11-22] update | Slide Production Workflow Markdown
- 新增：`outputs/slide-production-workflow.md`
- 格式：Markdown，內含 Mermaid流程圖與階段檢查表。
- 原始 `.mmd` 流程圖保留於 `outputs/slide-production-workflow.mmd`。

## [2026-11-22] update | Enlarged Workflow Graph
- 調整：Mermaid 流程圖由橫向改為直向分層。
- 強化：增加節點間距、階層間距與字體尺寸，改善 Markdown 預覽可讀性。
- 同步更新：`slide-production-workflow.md` 與 `slide-production-workflow.mmd`。

## [2026-11-22] output | Presentation Outline
- 產出：`outputs/presentation-outline.md`
- 狀態：已由使用者確認。
- 範圍：13 頁咖啡主題簡報大綱，保留手繪風格、assets 圖片與來源限制。
- 下一階段：逐頁撰寫內容腳本。

## [2026-11-22] output | Presentation Page Scripts
- 產出：`outputs/presentation-page-scripts.md`
- 範圍：13 頁逐頁標題、重點、講者口述、視覺指示與來源。
- 狀態：已由使用者確認；進入逐頁版面與 HTML 設計。

## [2026-11-22] final | Coffee Presentation Produced
- 產出：依確認大綱與逐頁腳本完成 `outputs/coffee-from-seed-to-cup.html`
- 結構：13 頁；涵蓋種植、處理、烘焙、沖煮、杯測與臺灣脈絡
- 設計：米白紙感、深咖啡文字、焦糖重點、手繪流程與 assets 圖片
- 功能：鍵盤、觸控、滑鼠翻頁、進度與列印版面

## [2026-11-23] update | Wiki Links on Each Slide
- 更新：13 頁投影片頁腳均加入對應 Wiki 連結。
- 層級：流程頁、概念頁、實體頁及來源頁依當頁內容列出。
- 範圍：維護與索引頁另連至 `AGENTS.md`、`index.md` 與 `log.md`。

## [2026-11-23] fix | Make GitHub Pages Wiki Links Visible
- 修正：將頁腳 Wiki 連結改為醒目膠囊標籤。
- 修正：將頁碼移至右上角，避免與右下角頁腳連結重疊。
- 同步：保留相對連結，讓連結可隨儲存庫或 Pages 路徑正確解析。

## [2026-11-23] output | Public HTML Wiki
- 產出：將 38 個 Wiki Markdown 頁面轉換為對應 `.html` 頁面。
- 更新：簡報 13 頁頁腳改用可公開瀏覽的 HTML 連結。
- 索引：根目錄 `index.html` 提供 Wiki 入口。

## [2026-11-23] update | Slide Wiki Topic Labels
- 更新：每頁頁腳改為直接顯示對應 Wiki 主題，不再使用超連結或連結膠囊。
- 範圍：13 頁均標示流程、實體、概念或來源主題。
- 視覺：保留焦糖色標題與虛線膠囊，避免破壞簡報版面。

## [2026-11-22] output | Coffee From Seed to Cup Slides
- 產出：`outputs/coffee-from-seed-to-cup.html`
- 內容：依 Wiki 主鏈條製作 13 頁簡報式投影片，涵蓋種植、處理、烘焙、沖煮、杯測、台灣脈絡與知識維護。
- 操作：支援方向鍵、Page Up/Page Down、Enter、空格、Home/End、觸控與滑鼠點擊。
- 輸出格式：單一 HTML，使用原始 assets 圖檔並支援列印。
