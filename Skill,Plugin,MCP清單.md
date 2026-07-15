# 本機 Claude 工具清單（Skill / Plugin / MCP / Agent）

> 盤點日期：2026-07-15　｜　由 toollist skill 自動產生（每次覆蓋＝永遠最新）
> 公開網頁：https://chensoo8911.github.io/my-claude-toollist/

## 🔑 觸發詞速查（24 個觸發詞 · 11 個 skill）

| 觸發詞 | 對應 Skill |
|---|---|
| `展開SVG` | **claude-figma-svg-expand** |
| `快照全md` | **claude-md-snapshot** |
| `claude通知音效` | **claude-notify-sounds** |
| `大事SOP` / `自己跑完複雜任務` / `下單卡` / `套用工作制度` / `①多步驟②可檢查③需迭代` | **claude-ops** |
| `大團出圖` | **claude-tnbt-export** |
| `我誰` / `幫我寫 CLAUDE.md` / `產生 instructions` / `設定一個角色／助理` / `whoami` | **claude-whoami** |
| `發版` | **command-push** |
| `加入ob` / `新增ob` | **obsidian-inbox** |
| `做名片` | **sv-card** |
| `列工具清單` / `更新工具清單` | **toollist** |
| `加入詞彙` / `記知識庫` / `整理學習庫` / `X 是什麼？` | **uiai-learn** |

## Skill（本機自建，共 11 個）

| Skill | 觸發詞 | 用途 |
|---|---|---|
| **claude-figma-svg-expand** | 展開SVG | 把 Figma 帶有 drop-shadow / 文字的 SVG「完全展開」成純幾何、可在 HTML 穩定顯示的 SVG |
| **claude-md-snapshot** | 快照全md | 把全域 CLAUDE.md 另存一份日期快照，作為大改前的歷史備份 |
| **claude-notify-sounds** | claude通知音效 | 在 macOS 安裝 / 設定 / 移除 Claude Code 的「純音效」hook |
| **claude-ops** | 大事SOP / 自己跑完複雜任務 / 下單卡 / 套用工作制度 / ①多步驟②可檢查③需迭代 | 一套讓 AI 助理「自己跑完複雜任務」的工作制度 |
| **claude-tnbt-export** | 大團出圖 | TNBT 大團（開發場次）從 Figma 批次存圖到本地交付夾的標準流程 |
| **claude-whoami** | 我誰 / 幫我寫 CLAUDE.md / 產生 instructions / 設定一個角色／助理 / whoami | 把使用者一句話的「你是誰＋規則」，轉成一份結構完整、可直接當作角色設定的 CLAUDE.md，存進目前資料夾 |
| **command-push** | 發版 | 個人維護 repo 的發版自動化（CHANGELOG→commit→tag→push→Release 五步） |
| **obsidian-inbox** | 加入ob / 新增ob | 把當下內容存進使用者的 Obsidian 收件匣 |
| **sv-card** | 做名片 | 公司名片自動化製作 |
| **toollist** | 列工具清單 / 更新工具清單 | 盤點本機 Claude 環境並同步清單 |
| **uiai-learn** | 加入詞彙 / 記知識庫 / 整理學習庫 / X 是什麼？ | UIAI 學習記錄工作流 |

## Plugin（已啟用，共 4 個）

| Plugin | 版本 | 來源 marketplace |
|---|---|---|
| **figma** | 2.2.81 | claude-plugins-official |
| **frontend-design** | unknown | claude-plugins-official |
| **obsidian** | 1.0.1 | obsidian-skills |
| **ui-ux-pro-max** | 2.5.0 | ui-ux-pro-max-skill |

## MCP Server（共 6 個）

| MCP | 類型 | 狀態 |
|---|---|---|
| **claude.ai Slack** | claude.ai connector | — |
| **claude.ai Gmail** | claude.ai connector | — |
| **claude.ai Notion** | claude.ai connector | — |
| **plugin:figma:figma** | plugin 內建 | Connected |
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

## 終端機工具（三劍客，共 3 項）

| 工具 | 呼叫方式 | 用途 |
|---|---|---|
| **小G** | 小G 問題 ／ 小G：問題 | 量產苦力（Gemini）：草稿、翻譯、清單擴寫、格式轉換；產出自動落檔 |
| **小L** | 小L 加入／摘要／：問題 | 文件圖書館員（NotebookLM）：吞 PDF／網址，給有出處的問答與規格摘要 |
| **審查協議** | 對話打 .  | Claude 讀雜工落檔做漏洞審查＋修正定稿（三劍客的主廚環節） |

---
> 🔒 本清單只含工具名稱與用途，不含任何密鑰、token 或 API 串接資訊。
