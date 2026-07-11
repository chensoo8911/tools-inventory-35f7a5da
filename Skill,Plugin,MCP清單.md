# 本機 Claude 工具清單（Skill / Plugin / MCP / Agent）

> 盤點日期：2026-07-11　｜　由 local-inventory skill 自動產生（每次覆蓋＝永遠最新）
> 公開網頁：https://chensoo8911.github.io/tools-inventory-35f7a5da/

## 🔑 觸發詞速查（13 個觸發詞 · 9 個 skill）

| 觸發詞 | 對應 Skill |
|---|---|
| `claude通知音效` | **claude-notify-sounds** |
| `發版` | **command-push** |
| `列工具清單` / `更新工具清單` | **local-inventory** |
| `大事SOP` | **loop-sop** |
| `快照全md` | **md-snapshot** |
| `加入ob` / `新增ob` | **obsidian-inbox** |
| `做名片` | **sv-card** |
| `大團出圖` | **tnbt-export** |
| `加入詞彙` / `記知識庫` / `整理學習庫` | **uiai-learn** |

## Skill（本機自建，共 9 個）

| Skill | 觸發詞 | 用途 |
|---|---|---|
| **claude-notify-sounds** | claude通知音效 | 在 macOS 安裝 / 設定 / 移除 Claude Code 的「純音效」hook |
| **command-push** | 發版 | 個人維護 repo 的發版自動化（CHANGELOG→commit→tag→push→Release 五步） |
| **local-inventory** | 列工具清單 / 更新工具清單 | 盤點本機 Claude 環境並同步清單 |
| **loop-sop** | 大事SOP | 大事／重複性工作的 Loop Engineering（下單卡＋自跑循環＋停止條件＋護欄） |
| **md-snapshot** | 快照全md | 把全域 CLAUDE.md 另存一份日期快照，作為大改前的歷史備份 |
| **obsidian-inbox** | 加入ob / 新增ob | 把當下內容存進使用者的 Obsidian 收件匣 |
| **sv-card** | 做名片 | 公司名片自動化製作 |
| **tnbt-export** | 大團出圖 | 活動視覺批次出圖（Figma→本地交付夾） |
| **uiai-learn** | 加入詞彙 / 記知識庫 / 整理學習庫 | UIAI 學習記錄工作流 |

## Plugin（已啟用，共 4 個）

| Plugin | 版本 | 來源 marketplace |
|---|---|---|
| **figma** | 2.2.78 | claude-plugins-official |
| **frontend-design** | unknown | claude-plugins-official |
| **obsidian** | 1.0.1 | obsidian-skills |
| **ui-ux-pro-max** | 2.5.0 | ui-ux-pro-max-skill |

## MCP Server（共 8 個）

| MCP | 類型 | 狀態 |
|---|---|---|
| **claude.ai Trimble SketchUp** | claude.ai connector | Connected |
| **claude.ai Google Drive** | claude.ai connector | Connected |
| **claude.ai Slack** | claude.ai connector | Needs auth |
| **claude.ai Gmail** | claude.ai connector | Connected |
| **claude.ai Google Calendar** | claude.ai connector | Connected |
| **plugin** | 本機 server | Connected |
| **illustrator** | 本機 server | Connected |
| **playwright** | 本機 server | Connected |

## Agent（自製 2 個＋內建 6 個）

| Agent | 來源 | 用途 | 工具權限 |
|---|---|---|---|
| **uiai-recorder** | 自製 | UIAI 學習庫記錄員 | Read, Edit, Write, Glob, Grep, Bash |
| **verifier** | 自製 | Fresh-context 驗收員（Maker-Checker 的 Checker） | Read, Glob, Grep, Bash |
| **general-purpose** | 內建 | 萬用型：研究、找程式碼、多步驟雜活 | — |
| **Explore** | 內建 | 唯讀搜索型：大範圍掃檔案，只回結論 | — |
| **Plan** | 內建 | 架構規劃型：設計實作計畫、評估取捨 | — |
| **claude** | 內建 | FleetView 預設萬用款 | — |
| **claude-code-guide** | 內建 | Claude Code／API 問題專家 | — |
| **statusline-setup** | 內建 | 設定終端機狀態列專用 | — |

---
> 🔒 本清單只含工具名稱與用途，不含任何密鑰、token 或 API 串接資訊。
