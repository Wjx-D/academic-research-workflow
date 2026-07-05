---
name: nature-reviewer-response
description: >-
  起草、审核和修改逐点回复审稿人的Response Letter。支持大修/小修回复、
  Cover Letter、修订稿标红修改。处理审稿意见分类、回复策略制定、
  修改位置映射。
  触发词：response to reviewers、rebuttal letter、major revision、
  审稿意见回复、修回信、返修邮件、逐点回复。
---

# Nature Reviewer Response — 审稿意见回复

基于 `Yuan1z0825/nature-skills` 的 `nature-response` 技能。

## 核心功能

1. **意见分类**：Critical / Major / Minor / Suggestion
2. **回复策略**：同意修改、合理解释、礼貌反驳
3. **逐点回复**：每一点对应明确回复和修改位置
4. **格式输出**：LaTeX/Word模板

## 工作流程

1. 解析审稿邮件/意见
2. 分类每条意见
3. 制定回复策略
4. 起草逐点回复
5. 映射修改位置
6. QA检查

## 核心原则

- 每条意见必须回应，不能遗漏
- 修改位置明确标注（行号/章节）
- 礼貌专业，即使不同意
- 不虚构实验或数据

## 相关技能

- `nature-reviewer` — 了解审稿人视角
- `academic-paper` (revision mode) — 执行修改
