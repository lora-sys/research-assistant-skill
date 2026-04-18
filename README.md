# research-assistant

科研全流程提示词技能，支持文献检索到论文发表完整链路。

## 安装

```bash
npx skill add lora-sys/research-assistant-skill --path ~/.claude/skills/
```

## 五大模块

| 模块 | 文件 | 用途 |
|------|------|------|
| 文献检索 | `references/01-literature-retrieval.md` | 找论文、查文献、查技术方法 |
| 学术脉络梳理 | `references/02-academic-context.md` | 概念演进、后续改进、找奠基性工作 |
| 科研提示词完整版 | `references/03-paper-writing.md` | 翻译、润色、摘要、标题、参考文献、降重、审稿回复等（Prompt 1-49） |
| 技术路线图 | `references/04-tech-roadmap.md` | Gemini + Drawio 生成可编辑技术路线图 |
| 论文Prompt集合 | `references/05-paper-prompts.md` | 科研绘图、降AIGC、模型选择建议 |

## 使用方式

直接描述你的需求，skill 会根据场景加载对应分类的提示词原文使用。

## 提示词原文原则

所有 reference 文件中的 Prompt 原文均保持原始内容不变，只做分类映射加载，不修改任何提示词文本。

## 内容来源

- `01-literature-retrieval.md` + `02-academic-context.md` → Gemini3.1高级文献提示词
- `03-paper-writing.md` → 科研提示词详细版（1-49条）
- `04-tech-roadmap.md` → Gemini绘制可编辑的技术路线图教程
- `05-paper-prompts.md` → 论文Prompt集合
