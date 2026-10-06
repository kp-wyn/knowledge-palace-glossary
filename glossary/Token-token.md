---
id: KP-TERM-088
term: Token
en: Token
category: 架构 / Architecture
synonyms: 令牌，Token 消耗 / Token Consumption，上下文窗口 / Context Window
attribution: 行业通用概念，知识宫殿体系重新释义 / Industry concept redefined within Knowledge Palace
created: 2026-10-06
updated: 2026-10-06
version: 1.0
status: 已稳定 / Stable
---

# Token

## 中文

Token（令牌）在知识宫殿体系里有两层含义：

1. **模型工作的计量单位**——AI 每读入、生成一段内容都按 Token 计耗、计费，是 AI 工作的“度量衡”；
2. **上下文资源**——一次对话或任务能使用的上下文窗口（context window）以 Token 为上限，决定 AI 一次能“看到”多少资料。

知识宫殿据此做**成本监控**（每条流水线、每个技能的 Token 消耗与超支告警）与**上下文管理**（长文档分块、检索裁剪），把 Token 当作可预算、可配额、可核算的生产资源。

## English

In the Knowledge Palace, Token has two meanings:

1. **The unit of measure for model work** — everything AI reads in or generates is metered and billed in tokens, the “unit” of AI work;
2. **A context resource** — the context window of a conversation or task is capped in tokens, determining how much material AI can “see” at once.

The palace uses this for **cost monitoring** (token consumption and overrun alerts per pipeline and skill) and **context management** (chunking long documents, trimming retrieval), treating tokens as a production resource that can be budgeted, quotaed and accounted for.

## 典型场景 / Typical Scenarios

- 流水线与技能的成本监控、超支告警 / Cost monitoring and overrun alerts for pipelines and skills
- 长文档、多资料的上下文窗口管理 / Context-window management for long documents and many sources
- 内部 Token 成本与毛利核算（内部资料，不公开） / Internal token-cost and margin accounting (internal, not public)

## 关联 / Related Terms

- [治理控制面看板 · Governance Control Plane](./治理控制面看板-governance-control-plane.md)
- [技能治理层 · Skill Governance Layer](./技能治理层-skill-governance-layer.md)
- [流水线技能 · Pipeline Skill](./流水线技能-pipeline-skill.md)

---
© KP-4+1 Knowledge Palace · kp-wyn · v1.0
