---
name: nature-reviewer
description: >-
  模拟Nature风格审稿人评估，从审稿人视角（非作者回复）进行预审。
  输出3份独立审稿报告+交叉综合意见。评估原创性、科学重要性、跨学科读者群、
  技术严谨性、非专业人士可读性。
  触发词：Nature reviewer、预投稿评审、reviewer report、审稿人视角、
  模拟审稿、预审、投稿前自审。
---

# Nature Reviewer — 审稿人视角评估

基于 `Yuan1z0825/nature-skills` 的 `nature-reviewer` 技能。

## 核心功能

1. **3份独立报告**：Reviewer 1/2/3 从不同角度评估
2. **综合意见**：交叉综合，识别共识与分歧
3. **评估维度**：原创性、科学重要性、跨学科可读性、技术严谨性
4. **适用场景**：投稿前预审、修改前评估

## 评估维度

- Originality（原创性）
- Scientific Importance（科学重要性）
- Interdisciplinary Readership（跨学科读者群）
- Technical Soundness（技术严谨性）
- Readability for Nonspecialists（非专业人士可读性）

## 注意

- 不虚构审稿人身份、专业、机构
- 区分"有支持"、"薄弱"、"无法评估"
- 不声称编辑最终决定

## 相关技能

- `nature-reviewer-response` — 撰写回复信
- `academic-paper-reviewer` — 更完整的多视角评审
