---
para: identity
type: 目錄說明
status: active
summary: AI Agent 身份定義（進階功能）
---

# Agents

> AI Agent 身份定義 — 定義「AI 助理的不同角色」
> 這是**進階功能**，初學者可以先跳過

## 這是什麼？

當你需要讓 AI 扮演不同角色時（例如技術顧問、財務顧問），可以在這裡定義每個角色的職責和行為準則。

## 成員

| Agent | Label | 說明 |
|-------|-------|------|
| [[CloudPM]] | `team:cloud-pm` | 雲端PM — AWS/騰訊雲產品架構、帳務、合作模式 |
| [[SecurityPM]] | `team:security-pm` | 資安PM — Cloudflare/SSL/資安檢測/ISO 法規 |
| [[CFO]] | `team:cfo` | 財務長 — 產品毛利/營收分析 |
| [[DailyOps]] | `team:ops` | 日常營運助理 — 任務追蹤、跨部門事項 |
| [[Unassigned]] | `team:template` | 未指定角色範本 — 複製後可定義新角色 |

## 對學員的建議

1. **初學者**：先不用管這個資料夾，專注於基本的 PARA 和 Identity
2. **進階使用**：當你需要讓 AI 有專業角色時，參考這些定義
3. **可以刪除**：如果不需要多 Agent，整個 Agents/ 資料夾可以刪除

## Agent 共同規範

- 遵守 [[Areas/AI-Governance/Policies/anti-phishing|防釣魚政策]]
- 共用帳號操作必須署名
