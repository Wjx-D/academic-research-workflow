---
name: academic-research-workflow
description: >-
  学术研究全流程 Workflow Skills — 从选题、检索、综述、统计、绘图、写作、润色到投稿汇报的完整技能集。
---

# Academic Research Workflow

学术研究全流程 Workflow Skills — 从选题、检索、综述、统计、绘图、写作、润色到投稿汇报的完整技能集。

> 整合自 [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) 和 [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) 两大开源学术技能库，并新增3个原创技能。

---

## 技能索引

| 技能 | 状态 | 功能 | 触发词 |
|------|------|------|--------|
| [`scientific-brainstorming`](skills/scientific-brainstorming/) | **新建** | 科研选题与头脑风暴 | 选题、brainstorm、研究构想 |
| [`nature-academic-search`](skills/nature-academic-search/) | 适配 | 多源文献检索与管理 | 文献检索、查文献、引文核对 |
| [`literature-review`](skills/literature-review/) | **新建** | 系统综述与Meta分析 | 系统综述、Meta分析、PRISMA |
| [`academic-research-suite`](skills/academic-research-suite/) | 适配 | 全流程统筹管理 | 学术pipeline、全流程 |
| [`statistical-analysis`](skills/statistical-analysis/) | **新建** | 统计分析与研究设计 | 统计分析、样本量、效应量 |
| [`nature-figure`](skills/nature-figure/) | 适配 | 投稿级科研绘图 | Nature figure、科研绘图 |
| [`nature-writing`](skills/nature-writing/) | 适配 | 论文起草 | 论文写作、学术写作 |
| [`nature-polishing`](skills/nature-polishing/) | 适配 | 文本润色与翻译 | 润色、proofreading |
| [`nature-reviewer`](skills/nature-reviewer/) | 适配 | 预审稿评估 | 审稿人视角、模拟审稿 |
| [`nature-reviewer-response`](skills/nature-reviewer-response/) | 适配 | 审稿意见回复 | response letter、修回信 |
| [`nature-data`](skills/nature-data/) | 适配 | Data Availability声明 | 数据可用性、FAIR |
| [`nature-paper2ppt`](skills/nature-paper2ppt/) | 适配 | 论文转PPT汇报 | paper PPT、文献汇报 |

---

## 完整研究流程

```
选题阶段 → 检索阶段 → 分析阶段 → 写作阶段 → 审稿阶段 → 汇报阶段
    ↓          ↓          ↓          ↓          ↓          ↓
scientific-  nature-   statistical- nature-   nature-   nature-
brainstorm   academic-   analysis   writing   reviewer  paper2ppt
             search                          response
               ↓                             ↓
          literature-                    academic-
            review                      research-suite
                                            ↓
                                        nature-
                                        polishing
                                            ↓
                                        nature-
                                         figure
                                            ↓
                                        nature-
                                          data
```

### 10阶段 Pipeline

| 阶段 | 名称 | 技能 | 产出物 |
|------|------|------|--------|
| 1 | **选题** | `scientific-brainstorming` | 研究问题、可行性分析 |
| 2 | **检索** | `nature-academic-search` | 文献库、检索策略 |
| 3 | **综述** | `literature-review` | 系统综述/Meta分析 |
| 4 | **统计** | `statistical-analysis` | 研究设计、样本量、分析方案 |
| 5 | **绘图** | `nature-figure` | 投稿级图表 |
| 6 | **写作** | `nature-writing` | 论文初稿 |
| 7 | **润色** | `nature-polishing` | 润色稿 |
| 8 | **数据** | `nature-data` | Data Availability声明 |
| 9 | **审稿** | `nature-reviewer` | 预审报告 |
| 10 | **回复** | `nature-reviewer-response` | Response Letter |
| 11 | **汇报** | `nature-paper2ppt` | 汇报PPT |

---

## 安装使用

### 作为 Kimi 技能使用

将本仓库克隆到本地技能目录：

```bash
git clone https://github.com/Wjx-D/academic-research-workflow.git
```

然后在 Kimi 中通过技能管理加载所需技能。

### 作为参考文档使用

每个技能目录包含 `SKILL.md` 文件，可直接阅读了解工作流程和最佳实践。

---

## 技能来源与致谢

| 技能 | 来源 | 许可证 |
|------|------|--------|
| `nature-academic-search` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-figure` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-writing` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-polishing` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-reviewer` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-reviewer-response` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-data` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `nature-paper2ppt` | [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) | 开源 |
| `academic-research-suite` | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | CC BY-NC 4.0 |
| `deep-research` (引用) | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | CC BY-NC 4.0 |
| `academic-paper` (引用) | [Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills) | CC BY-NC 4.0 |

**新建技能**（`scientific-brainstorming`, `literature-review`, `statistical-analysis`）基于上述技能库的设计哲学和最佳实践原创编写。

---

## 使用示例

### 示例1：从零开始写一篇论文

```
用户：我想研究"维持性血液透析患者高磷饮食管理"，请帮我完成整个流程

系统：
  Stage 1: scientific-brainstorming → 生成研究问题和可行性分析
  Stage 2: nature-academic-search → 检索相关文献
  Stage 3: statistical-analysis → 设计研究方案和样本量
  Stage 4: nature-writing → 起草论文
  Stage 5: nature-polishing → 润色文本
  Stage 6: nature-reviewer → 预审评估
  Stage 7: nature-reviewer-response → 模拟回复审稿意见
  Stage 8: nature-paper2ppt → 生成开题/汇报PPT
```

### 示例2：只需统计分析咨询

```
用户：我的研究是两组均数比较，效应量Cohen's d=0.5，α=0.05，效能80%，需要多少样本？

系统：statistical-analysis → 使用独立t检验样本量公式计算
  n = 2*(1.96+0.84)²*σ²/δ² = ...
  每组需要64人，考虑20%脱落率，最终每组需要80人
```

### 示例3：系统综述

```
用户：请帮我做一篇关于"血液透析患者瘙痒管理"的系统综述

系统：
  Step 1: literature-review → 设计综述方案(PICO)
  Step 2: nature-academic-search → 执行检索
  Step 3: literature-review → 筛选、质量评估、数据提取
  Step 4: statistical-analysis → Meta分析统计合成
  Step 5: nature-figure → 森林图、漏斗图
  Step 6: nature-writing → 撰写综述
```

---

## 贡献

欢迎提交 Issue 和 PR。如需新增技能或改进现有技能，请遵循以下原则：

1. 保持 SKILL.md 简洁（<500行）
2. 详细参考材料放在 references/ 目录
3. 脚本放在 scripts/ 目录
4. 遵循渐进式披露设计原则

---

## 更新日志

| 日期 | 版本 | 更新内容 |
|------|------|----------|
| 2026-07-06 | v1.0.0 | 初始发布，整合两大技能库，新增3个技能 |
