# service-hub：客戶信件回覆器

## Capability
AI 能夠在維護工作知識頁的情境下，
使用 content/ 的內容與 design/brief.md 的版型規範，
遵守 CLAUDE.md 的規則，完成信件回覆生成與更新。

## Boundary
AI 做/ 人做：reference 上面boundary的討論及決議

## 今日暫行規則
架構建立階段結束，現在可以讀取 source/ 與生成內容。
但以下三件事仍然禁止：
1. 不得自行決定資料矛盾如何處理，遇到矛盾必須停下來回報給我
2. 不得補寫 source/ 裡沒有的資訊，缺什麼就說缺什麼
3. 仍然不得讀取 restricted/
