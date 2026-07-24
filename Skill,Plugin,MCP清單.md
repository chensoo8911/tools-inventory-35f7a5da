# 本機 Claude 工具清單（Skill / Plugin / MCP / Agent）

> 盤點日期：2026-07-24　｜　由 toollist skill 自動產生（每次覆蓋＝永遠最新）
> 公開網頁：https://chensoo8911.github.io/my-claude-toollist-html/

## 🔑 觸發詞速查（26 個觸發詞 · 14 個 skill）

| 觸發詞 | 對應 Skill |
|---|---|
| `發版` | **claude-command-push** |
| `展開SVG` | **claude-figma-svg-expand** |
| `快照全md` | **claude-md-snapshot** |
| `claude通知音效` | **claude-notify-sounds** |
| `加入ob` / `新增ob` | **claude-obsidian-inbox** |
| `大事SOP` / `自己跑完複雜任務` / `下單卡` / `①多步驟②可檢查③需迭代` | **claude-ops** |
| `做名片` | **claude-sv-card** |
| `大團出圖` | **claude-tnbt-export** |
| `部署三劍客` / `裝三劍客` | **claude-triple-brain** |
| `我誰` / `幫我寫 CLAUDE.md` | **claude-whoami** |
| `how do I do X` / `find a skill for X` | **find-skills**（推測） |
| `制度健檢` / `規則體檢` | **my-claude-self-audit** |
| `列工具清單` / `更新工具清單` | **my-claude-toollist** |
| `加入詞彙` / `記知識庫` / `整理學習庫` / `X 是什麼？` | **my-claude-uiai-learn** |

## Skill（本機自建，共 16 個）

| Skill | 觸發詞 | 用途 |
|---|---|---|
| **apple-hig-expert** | — | "Audits and designs iOS/macOS/watchOS/visionOS interfaces ag |
| **claude-command-push** | 發版 | git repo 發版自動化 |
| **claude-figma-svg-expand** | 展開SVG | 把 Figma 帶有 drop-shadow / 文字的 SVG「完全展開」成純幾何、可在 HTML 穩定顯示的 SVG |
| **claude-md-snapshot** | 快照全md | 把全域 CLAUDE.md 另存一份日期快照，作為大改前的歷史備份 |
| **claude-notify-sounds** | claude通知音效 | 在 macOS 安裝 / 設定 / 移除 Claude Code 的「純音效」hook |
| **claude-obsidian-inbox** | 加入ob / 新增ob | 把當下內容存進使用者的 Obsidian 收件匣 |
| **claude-ops** | 大事SOP / 自己跑完複雜任務 / 下單卡 / ①多步驟②可檢查③需迭代 | 一套讓 AI 助理「自己跑完複雜任務」的工作制度 |
| **claude-sv-card** | 做名片 | StreetVoice 街聲名片自動化製作（TW 街聲版＋中子 BVI 版＋台灣中子版三種全自動；經典復刻款BVI 為第 |
| **claude-tnbt-export** | 大團出圖 | TNBT 大團（開發場次）從 Figma 批次存圖到本地交付夾的標準流程 |
| **claude-triple-brain** | 部署三劍客 / 裝三劍客 | 部署「三劍客」終端機 AI 協作環境：小G（Gemini 量產苦力）＋小L（NotebookLM 文件圖書館員）＋Cla |
| **claude-whoami** | 我誰 / 幫我寫 CLAUDE.md | 把使用者一句話的「你是誰＋規則」，轉成一份結構完整、可直接當作角色設定的 CLAUDE.md，存進目前資料夾 |
| **find-skills** | how do I do X / find a skill for X | Helps users discover and install agent skills when they ask  |
| **my-claude-self-audit** | 制度健檢 / 規則體檢 | 制度健檢顧問（Claude 進階玩家視角） |
| **my-claude-toollist** | 列工具清單 / 更新工具清單 | 盤點本機 Claude 環境並同步清單 |
| **my-claude-uiai-learn** | 加入詞彙 / 記知識庫 / 整理學習庫 / X 是什麼？ | UIAI 學習記錄工作流 |
| **"research-summarizer"** | — | "Structured research summarization agent skill for non-dev u |

## Plugin（已啟用，共 4 個）

| Plugin | 版本 | 來源 marketplace |
|---|---|---|
| **figma** | 2.2.81 | claude-plugins-official |
| **frontend-design** | unknown | claude-plugins-official |
| **obsidian** | 1.0.1 | obsidian-skills |
| **ui-ux-pro-max** | 2.5.0 | ui-ux-pro-max-skill |

## MCP Server（共 9 個）

| MCP | 類型 | 狀態 |
|---|---|---|
| **claude.ai Trimble SketchUp** | claude.ai connector | — |
| **claude.ai Google Drive** | claude.ai connector | — |
| **claude.ai Slack** | claude.ai connector | — |
| **claude.ai Gmail** | claude.ai connector | — |
| **claude.ai Google Calendar** | claude.ai connector | — |
| **plugin:figma:figma** | plugin 內建 | Connected |
| **illustrator** | 本機 server | Connected |
| **playwright** | 本機 server | Connected |
| **firecrawl** | 本機 server | Connected |

## Agent（自製 13 個＋內建 6 個）

| Agent | 來源 | 用途 | 工具權限 |
|---|---|---|---|
| **competitive-analyst** | 自製 | "Use when you need to analyze direct and indirect competitor | Read, Grep, Glob, WebFetch, WebSearch |
| **content-marketer** | 自製 | "Use this agent when you need to develop comprehensive conte | Read, Write, Edit, Glob, Grep, WebFetch, WebSearch |
| **content-quality-editor** | 自製 | "Use this agent before publishing any AI-generated content — | Read, Write, Edit, Bash |
| **market-researcher** | 自製 | "Use this agent when you need to analyze markets, understand | Read, Grep, Glob, WebFetch, WebSearch |
| **publish-safety-checker** | 自製 | Fresh-context 發版安檢員 | Read, Glob, Grep, Bash |
| **research-analyst** | 自製 | "Use this agent when you need comprehensive research across  | Read, Grep, Glob, WebFetch, WebSearch |
| **search-specialist** | 自製 | "Use when you need to find specific information across multi | Read, Grep, Glob, WebFetch, WebSearch |
| **system-critic** | 自製 | Fresh-context 制度質疑者（唱反調的那個） | Read, Glob, Grep, Bash, WebSearch, WebFetch |
| **trend-analyst** | 自製 | "Use when analyzing emerging patterns, predicting industry s | Read, Grep, Glob, WebFetch, WebSearch |
| **ui-designer** | 自製 | "Use this agent when designing visual interfaces, creating d | Read, Write, Edit, Bash, Glob, Grep |
| **uiai-recorder** | 自製 | UIAI 學習庫記錄員 | Read, Edit, Write, Glob, Grep, Bash |
| **ux-researcher** | 自製 | "Use this agent when you need to conduct user research, anal | Read, Grep, Glob, WebFetch, WebSearch |
| **verifier** | 自製 | Fresh-context 驗收員（Maker-Checker 的 Checker） | Read, Glob, Grep, Bash |
| **general-purpose** | 內建 | 萬用型：研究、找程式碼、多步驟雜活 | — |
| **Explore** | 內建 | 唯讀搜索型：大範圍掃檔案，只回結論 | — |
| **Plan** | 內建 | 架構規劃型：設計實作計畫、評估取捨 | — |
| **claude** | 內建 | FleetView 預設萬用款 | — |
| **claude-code-guide** | 內建 | Claude Code／API 問題專家 | — |
| **statusline-setup** | 內建 | 設定終端機狀態列專用 | — |

## 終端機工具（共 4 項）

| 工具 | 呼叫方式 | 用途 |
|---|---|---|
| **小G** | 小G 問題 ／ 小G：問題 | 量產苦力（Gemini）：草稿、翻譯、清單擴寫、格式轉換；產出自動落檔 |
| **小L** | 小L 加入／摘要／：問題 | 文件圖書館員（NotebookLM）：吞 PDF／網址，給有出處的問答與規格摘要 |
| **審查協議** | 對話打 .  | Claude 讀雜工落檔做漏洞審查＋修正定稿（三劍客的主廚環節） |
| **mole** | mo clean（預覽加 --dry-run） | Mac 深度清快取／釋放磁碟空間（Homebrew 安裝）；純手動、無自動排程 |

---
> 🔒 本清單只含工具名稱與用途，不含任何密鑰、token 或 API 串接資訊。
