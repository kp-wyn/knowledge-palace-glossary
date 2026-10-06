---
id: KP-TERM-090
term: 全链路审计
en: Full-Chain Audit
category: 技能治理 / Skill Governance
synonyms: 全程审计 / End-to-End Audit，操作留痕 / Operation Logging
attribution: 知识宫殿体系方法 / Method of Knowledge Palace System
created: 2026-10-06
updated: 2026-10-06
version: 1.0
status: 已稳定 / Stable
---

# 全链路审计

## 中文

比“审计追溯”更具体的方法：对技能 / Agent 的每一次运行，从**发起人、输入、调用的工具与技能、中间步骤、到最终输出**全程记录，可还原、可回放。所有关键动作留痕，责任可锚定到人，满足金融、医疗、政府的合规要求。

概念与价值可公开；审计日志的字段 schema、留存策略与具体实现属内部资料。

## English

A method more concrete than “audit & traceability”: for every run of a skill / agent, record the full chain — **initiator, input, tools and skills invoked, intermediate steps and final output** — so it can be reconstructed and replayed. Every key action leaves a trace and responsibility can be anchored to a person, meeting compliance in finance, healthcare and government.

The concept and value are public; the audit-log field schema, retention policy and implementation are internal.

## 典型场景 / Typical Scenarios

- 强合规客户要求每次技能调用可追溯、可审计 / Highly regulated clients requiring traceable, auditable skill calls
- 敏感操作（如导出客户数据）需审批留痕 / Approval and logging for sensitive operations such as data export
- 定期生成技能使用报告与质量报告 / Periodic skill-usage and quality reports

## 关联 / Related Terms

- [技能治理层 · Skill Governance Layer](./技能治理层-skill-governance-layer.md)
- [企业三层权限体系 · Enterprise Three-Layer Permission System](./企业三层权限体系-enterprise-three-layer-permission.md)
- [责任锚定 · Responsibility Anchoring](./责任锚定-responsibility-anchoring.md)
- [治理控制面看板 · Governance Control Plane](./治理控制面看板-governance-control-plane.md)

---
© KP-4+1 Knowledge Palace · kp-wyn · v1.0
