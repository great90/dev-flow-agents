---
stage: 需求规格
status: draft          # draft | frozen | superseded
requirement-id: REQ-yyyymmdd-N
frozen-at:             # 门1批准后填写日期
---

# 需求规格：<标题>

## 一句话目标

<用户视角：为谁解决什么问题>

## 用户故事

- US-1：作为 <角色>，我希望 <能力>，以便 <价值>。

## 功能需求

- FR-1 <可验证的陈述>（关联 US-1）
- FR-2 …

## 非功能需求

- NFR-1 <性能 / 安全 / 兼容 / 可观测约束>

## 验收标准

> 门1冻结后禁止放宽；变更只能走显式变更流程（记 decisions.md + 评估受影响切片）。

- AC-1（关联 FR-1）：Given <前置条件>，When <动作>，Then <可观察结果>。
- AC-2 …

## 开放问题与假设

- 引用 `assumptions.md` 编号（A-1, A-2…）；门1前应无"答案会改变实现"的开放问题。
