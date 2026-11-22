# Coffee LLM Wiki

以 LLM 維護的咖啡知識庫，主題為「咖啡從種子到一杯飲品」：
種植、處理、烘焙與沖煮。

## 目錄

- `AGENTS.md`：維護規範與操作工作流。
- `raw/`：不可修改的原始來源與媒體。
- `wiki/`：LLM 綜合、更新與維護的 Markdown 頁面。
- `index.md`：內容導向索引。
- `log.md`：chronological 操作紀錄。

## 使用方式

1. 將來源放入 `raw/sources/`。
2. 指示：「請 ingest <來源檔名>。」
3. 審閱摘要頁、跨頁更新與任何衝突。
4. 使用 Wiki 頁面進行深度查詢。
5. 定期執行 lint，處理孤兒頁、衝突與知識缺口。

## 輸出

- `outputs/coffee-from-seed-to-cup.html`：咖啡主題簡報式 HTML 投影片。
