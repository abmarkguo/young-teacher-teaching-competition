# 全国高校青年教师教学竞赛演练工具 | Young Teacher Teaching Competition Toolkit

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blue.svg)](https://github.com/abmarkguo)
[![中文](https://img.shields.io/badge/语言-中文-red.svg)]()
[![English](https://img.shields.io/badge/Language-English-blue.svg)]()
[![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)]()
[![Competition](https://img.shields.io/badge/青教赛-备赛工具-orange.svg)]()

> 站在专业评审角度，为参加「全国高校青年教师教学竞赛」的高校教师提供全流程模拟评审、诊断与优化指导。

---

## 概述 | Overview

本工具是面向参加**全国高校青年教师教学竞赛**（简称「青教赛」）的高校青年教师的**专业备赛演练工具**。站在竞赛评审专家的视角，对教师的教学设计、课堂教学、教学反思、PPT课件进行全流程模拟评审、诊断与优化指导。

This toolkit is designed for university young teachers participating in the **National Young Teacher Teaching Competition** of China. It provides professional mock evaluation, diagnosis, and optimization guidance from the perspective of competition judges, covering instructional design, classroom teaching, teaching reflection, and PPT courseware.

### 竞赛核心理念

> **「上好一门课」** — 以加强师德师风建设、锤炼教学基本功为着力点

### 三大环节与权重

| 环节 | 权重 | 说明 |
|------|------|------|
| 教学设计 | 20% | 以1个学时为基本单位的教学活动设想与安排 |
| 课堂教学 | 75% | 现场抽签进行15-20分钟模拟课堂教学 |
| 教学反思 | 5% | 课后45分钟内现场撰写500字反思材料 |

---

## 八大核心功能

| 功能 | 说明 |
|------|------|
| **教学设计评审与优化** | 按官方评分细则六大维度逐项打分，输出评审报告与优化建议 |
| **课堂教学模拟评审** | 基于讲稿/PPT/音频，模拟现场课堂四维度评审（教学内容/组织/语言教态/特色） |
| **教学反思撰写辅导** | 从教学理念、教学方法、教学过程三维度辅导撰写500字反思 |
| **PPT设计与内容评审** | 从结构化、精悍性、美观度、富媒体四维度逐页评审PPT |
| **授课音频全方位分析** | 音频转写后从语言规范/语速节奏/启发性提问/知识密度/课程思政/互动设计/AI赋能七维度分析 |
| **五大学科组别适配** | 文科/理科/工科/医科/思政课专项，五组等深+特色模块 |
| **竞赛层级动态匹配** | 校赛(2-3学时)→省赛(5学时)→国赛(16学时)动态适配 |
| **综合备赛诊断报告** | 全流程模拟评审，输出综合评分、优势分析、问题诊断、改进路线图 |

---

## 五大学科组别

| 组别 | 涵盖学科 | 核心特色 |
|------|----------|----------|
| **文科** | 哲学/经济学/法学/教育学/文学/历史学/管理学/艺术学 | 人文思辨·文化底蕴·社会价值 |
| **理科** | 理学 | 逻辑推演·科学方法·知识链条 |
| **工科** | 工学/农学 | 工程实践·前沿科技·产业需求 |
| **医科** | 医学 | 临床案例·基础临床融合·医者仁心 |
| **思想政治课专项** | 思想政治理论课 | 价值引领·问题链闭环·青年叙事 |

---

## 文件结构

```
young-teacher-teaching-competition/
├── SKILL.md                          # 核心指令文件（8大功能定义）
├── README.md                         # 中英文说明（本文件）
├── LICENSE                           # MIT许可证
├── CITATION.cff                      # 学术引用
├── .gitignore
├── references/                       # 9个专业参考文档
│   ├── competition-rules-reference.md       # 竞赛规则完整参考
│   ├── scoring-rubrics-detailed.md          # 详细评分细则
│   ├── track-specific-guide.md              # 五大学科组别特色指导
│   ├── teaching-design-guide.md             # 教学设计撰写指南
│   ├── classroom-teaching-guide.md          # 课堂教学展示策略
│   ├── teaching-reflection-guide.md         # 教学反思撰写指南
│   ├── ppt-design-competition-guide.md      # 竞赛PPT设计指南
│   ├── audio-analysis-guide.md              # 授课音频分析指南
│   └── improvement-strategy-guide.md        # 改进策略与备赛训练指南
├── assets/                           # 9个评审模板与清单
│   ├── teaching-design-template.md          # 教学设计模板
│   ├── teaching-design-review-checklist.md  # 教学设计评审清单
│   ├── classroom-evaluation-form.md         # 课堂教学评分表
│   ├── teaching-reflection-template.md      # 教学反思模板
│   ├── ppt-review-checklist.md              # PPT评审清单
│   ├── audio-analysis-report-template.md    # 音频分析报告模板
│   ├── comprehensive-score-report.md        # 综合评分报告模板
│   ├── track-requirements-quickref.md       # 各组别要求速查
│   └── competition-level-matrix.md          # 竞赛层级要求矩阵
└── docs/
    └── images/                      # SVG流程图
        ├── competition-architecture.svg      # 工具架构图
        ├── scoring-rubrics-overview.svg      # 评分体系总览
        └── preparation-workflow.svg          # 备赛流程图
```

---

## 评分标准

### 教学设计（满分20分）

| 维度 | 分值 |
|------|------|
| 立德树人 | 2分 |
| 学科前沿 | 4分 |
| 教学目标 | 4分 |
| 重点难点 | 4分 |
| 进程组织 | 4分 |
| 文字表达 | 2分 |

### 课堂教学（满分75分）

| 维度 | 分值 |
|------|------|
| 教学内容（立德树人/理论联系实际/学术性/学科前沿/重点突出） | 30分 |
| 教学组织（以学生为中心/启发性/时间管理/教学手段/板书设计） | 30分 |
| 语言教态（语言表达/肢体语言/仪表亲和） | 10分 |
| 教学特色 | 5分 |

### 教学反思（满分5分）

| 维度 | 分值 |
|------|------|
| 教学理念反思 | ~1.7分 |
| 教学方法反思 | ~1.7分 |
| 教学过程反思 | ~1.6分 |

---

## 关键特性

- **专业评审视角**：严格对标第七届全国高校青年教师教学竞赛官方评分细则
- **五大学科覆盖**：文科/理科/工科/医科/思想政治课专项，等深+特色模块
- **三级竞赛兼容**：校赛(2-3学时)→省赛(5学时)→国赛(16学时)动态适配
- **音频全方位分析**：七维度量化分析，覆盖55分评分项
- **课程思政评审**：对标"像盐溶于水"标准，评估融入自然度
- **AI赋能评估**：对标最新评分标准中AI赋能教学应用维度
- **获奖经验融入**：融入第七届国赛获奖选手经验和策略

---

## 竞赛背景

全国高校青年教师教学竞赛由**中华全国总工会**和**教育部**联合主办，是目前参与面最广、学科门类最全、组织规模最大的全国性高水平教学类竞赛。

- 第七届（2024年）：上海交通大学举办，2028所高校参与，30余万青年教师参与，央广网全程直播
- 竞赛每三年举办一届
- 获奖选手在教师职称评审中体现教育教学实绩

---

## 致谢

感谢济南陈鹏教授的鼎力支持

## Acknowledgments

Special thanks to Professor Chen Peng from Jinan for his invaluable support.

---

## 许可证 | License

[MIT License](LICENSE)

## 引用 | Citation

请参考 [CITATION.cff](CITATION.cff) 进行学术引用。

## 关键词 | Keywords

`青教赛` `教学竞赛` `青年教师` `教学设计` `课堂教学` `教学反思` `课程思政` `AI赋能教学` `高等教育` `教师发展` `teaching-competition` `instructional-design` `classroom-teaching` `higher-education` `faculty-development`
