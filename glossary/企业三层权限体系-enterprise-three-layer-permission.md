---
id: KP-TERM-089
term: 企业三层权限体系
en: Enterprise Three-Layer Permission System
category: 技能治理 / Skill Governance
synonyms: 三层权限体系 / Three-Layer Permission，企业权限体系设计 / Enterprise Permission Design
attribution: 知识宫殿体系原创整合 / Original integration by Knowledge Palace System
created: 2026-10-06
updated: 2026-10-06
version: 1.0
status: 已稳定 / Stable
---

# 企业三层权限体系

## 中文

企业级知识宫殿对“谁能做什么”的权限设计框架，分三层：

| 权限层 | 管什么 | 典型内容 |
| ---- | ---- | ---- |
| **数据权限** | 能看哪些数据 | 客户 / 部门 / 密级范围，客户数据按客户隔离 |
| **功能权限** | 能用哪些能力 | 技能 / 模块 / 工具的使用授权 |
| **操作权限** | 能执行哪些动作 | 查看 / 编辑 / 审批 / 导出 |

三层正交组合，配合角色（如 **OWNER / EDITOR / VIEWER / AUDITOR**）与客户数据隔离，构成技能治理的权限基座。概念框架可公开；具体到某客户的权限矩阵与配置模板属内部交付物。

## English

The permission-design framework for an enterprise Knowledge Palace, in three layers:

| Permission Layer | Controls | Typical Content |
| ---- | ---- | ---- |
| **Data permission** | which data one can see | client / department / confidentiality scope, client data isolated per client |
| **Function permission** | which capabilities one can use | authorization to skills / modules / tools |
| **Operation permission** | which actions one can perform | view / edit / approve / export |

The three layers combine orthogonally, working with roles (**OWNER / EDITOR / VIEWER / AUDITOR**) and client-data isolation to form the permission base of skill governance. The conceptual framework is public; a specific client’s permission matrix and configuration template are internal deliverables.

## 典型场景 / Typical Scenarios

- 多角色、多部门的企业知识宫殿 / Enterprise palaces with multiple roles and departments
- 客户数据需按客户隔离、敏感操作需审批 / Client-data isolation and approval for sensitive operations
- 金融、医疗、政府的权限合规 / Permission compliance in finance, healthcare and government

## 关联 / Related Terms

- [技能治理层 · Skill Governance Layer](./技能治理层-skill-governance-layer.md)
- [企业级知识宫殿 · Enterprise Knowledge Palace](./企业级知识宫殿-enterprise-knowledge-palace.md)
- [全链路审计 · Full-Chain Audit](./全链路审计-full-chain-audit.md)
- [治理控制面看板 · Governance Control Plane](./治理控制面看板-governance-control-plane.md)

---
© KP-4+1 Knowledge Palace · kp-wyn · v1.0
