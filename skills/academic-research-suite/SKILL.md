---
name: academic-research-suite
description: >-
  学术研究全流程统筹管理。从选题、检索、综述、统计、绘图、写作、润色、
  审稿回复到汇报的完整workflow协调。支持10阶段pipeline：
  研究→写作→诚信检查→审稿→修改→再审稿→再修改→最终检查→定稿→过程总结。
  触发词：学术研究流程、论文pipeline、全流程、学术workflow、
  research pipeline、论文全流程、统筹管理。
---

# Academic Research Suite — 学术研究全流程统筹

基于 `Imbad0202/academic-research-skills` 的 `academic-pipeline` 技能。

## 完整Pipeline（10阶段）

```
Stage 1: RESEARCH      → deep-research / scientific-brainstorming
     ↓
Stage 2: WRITE         → academic-paper / nature-writing
     ↓
Stage 2.5: INTEGRITY   → 诚信验证（引用、数据100%验证）
     ↓
Stage 3: REVIEW        → academic-paper-reviewer / nature-reviewer
     ↓
Stage 4: REVISE        → academic-paper (revision)
     ↓
Stage 3': RE-REVIEW    → 验证审稿（revision是否回应了意见）
     ↓
Stage 4': RE-REVISE    → 二次修改（如需要）
     ↓
Stage 4.5: FINAL INT.  → 最终诚信检查（必须100%通过）
     ↓
Stage 5: FINALIZE      → 格式转换（LaTeX/DOCX/PDF）
     ↓
Stage 6: SUMMARY       → 过程总结报告
```

## 可用技能索引

| 阶段 | 技能 | 功能 |
|------|------|------|
| 选题 | `scientific-brainstorming` | 选题脑暴与可行性评估 |
| 检索 | `nature-academic-search` | 多源文献检索 |
| 综述 | `literature-review` | 系统综述与Meta分析 |
| 统计 | `statistical-analysis` | 统计分析与研究设计 |
| 绘图 | `nature-figure` | 投稿级图表制作 |
| 写作 | `nature-writing` | 论文起草 |
| 润色 | `nature-polishing` | 文本润色与翻译 |
| 数据 | `nature-data` | Data Availability声明 |
| 审稿 | `nature-reviewer` | 预审稿评估 |
| 回复 | `nature-reviewer-response` | 审稿意见回复 |
| 汇报 | `nature-paper2ppt` | 论文转PPT |

## 核心原则

1. **强制检查点**：每阶段完成后需用户确认
2. **诚信验证**：Stage 2.5和4.5不可跳过
3. **两阶段审稿**：初稿评审+修改后验证
4. **最大修改轮次**：2轮
5. **用户可控**：可随时暂停、调整、退出

## 使用方式

**完整流程**：
```
我想写一篇关于[主题]的论文，请帮我完成从研究到投稿的全流程
```

**中途进入**：
```
我已经有了论文草稿，帮我审稿和修改
```

**单阶段调用**：
```
请帮我检索关于[主题]的文献
请帮我设计这个研究的统计方案
请帮我润色这段讨论部分
```

## 相关技能

- `deep-research` — 深度研究（Stage 1）
- `academic-paper` — 论文写作（Stage 2/4）
- `academic-paper-reviewer` — 多视角评审（Stage 3/3'）
