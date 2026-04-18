---
name: research-assistant
description: 科研助手技能，支持文献检索、学术脉络梳理、论文写作润色、技术路线图生成等全流程科研任务。当用户提及以下场景时触发：(1) 查找/检索文献、找论文、找参考；(2) 梳理学术脉络、概念演进、后续改进；(3) 论文润色、中英互译、改写降重、语法检查；(4) 写摘要、Cover letter、取标题；(5) 参考文献格式检查、APA校正；(6) 绘制技术路线图、生成Drawio图；(7) 科研配图、降AIGC；(8) 上传PDF/图片后解读；(9) 图表生成、数据可视化；(10) 任何SCI论文写作相关任务。
---

# 科研助手 (research-assistant)

科研全流程提示词技能，支持文献检索到论文发表完整链路。

## 使用方式

直接描述你的需求，skill 会加载对应分类的提示词原文（见下方分类索引）。

## 五大模块索引

| 模块 | 用途 | 何时加载 |
|------|------|---------|
| [01-literature-retrieval.md](references/01-literature-retrieval.md) | 文献检索 | 需要找论文、查文献、查技术方法 |
| [02-academic-context.md](references/02-academic-context.md) | 学术脉络梳理（概念演进+后续改进） | 梳理研究领域发展脉络、找奠基性工作 |
| [03-paper-writing.md](references/03-paper-writing.md) | 科研提示词完整版（1-49条） | 翻译、润色、摘要、标题、参考文献、降重、审稿回复等 |
| [04-tech-roadmap.md](references/04-tech-roadmap.md) | Gemini + Drawio 技术路线图 | 生成可编辑的技术路线图 |
| [05-paper-prompts.md](references/05-paper-prompts.md) | 论文Prompt集合 | 科研绘图、降AIGC、模型选择建议 |

## 快速指引

**文献检索** → 读 `01-literature-retrieval.md`，直接使用其中的检索 Prompt

**梳理脉络** → 读 `02-academic-context.md`，找"概念演进"或"后续改进"对应的 Prompt

**论文润色/翻译/改写** → 读 `03-paper-writing.md`，按编号（1-49）找到对应提示词

**生成技术路线图** → 读 `04-tech-roadmap.md`，按步骤在 Gemini + Drawio 中操作

**科研绘图/降AIGC** → 读 `05-paper-prompts.md`，使用对应 Prompt

## 提示词原文原则

所有 reference 文件中的 Prompt 原文均保持原始内容不变，只做分类映射加载，不修改任何提示词文本。
