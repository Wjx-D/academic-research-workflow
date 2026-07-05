---
name: nature-academic-search
description: >-
  多源学术文献检索、引文验证与参考文献管理。支持PubMed、CrossRef、arXiv、
  Scopus等数据库的联合检索，引文格式转换(.ris/.bib/.enw)，MeSH检索策略构建，
  严格他引分析。适用于系统性检索、引文核对、参考文献整理、文献去重。
  触发词：文献检索、查文献、找文献、引文核对、参考文献管理、MeSH检索、
  文献去重、严格他引、学术搜索。
---

# Nature Academic Search — 学术文献检索

基于 `Yuan1z0825/nature-skills` 的 `nature-academic-search` 技能。

## 核心功能

1. **多源检索**：PubMed, CrossRef, arXiv, Scopus, Semantic Scholar
2. **引文验证**：DOI验证、引文存在性检查
3. **格式转换**：.nbib ↔ .ris ↔ .bib ↔ .enw
4. **MeSH策略**：PubMed主题词检索策略构建
5. **他引分析**：严格独立他引统计、高影响力引用者识别

## 工作流

```
1. 明确检索需求
2. 选择数据库（T1→T2→T3降级策略）
3. 构建检索式（关键词/MeSH/布尔逻辑）
4. 执行检索与去重
5. 筛选与导出
6. 引文管理与格式转换
```

## 相关技能

- `literature-review` — 系统性文献综述
- `deep-research` — 深度研究
- `nature-citation` — CNS引用管理
