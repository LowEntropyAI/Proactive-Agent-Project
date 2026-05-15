# Need Help? Designing Proactive AI Assistants for Programming

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | CHI 2025 |
| **arXiv ID** | [arXiv:2410.04596](https://arxiv.org/abs/2410.04596) |
| **首发日期** | 2024 年 10 月 |
| **领域** | HCI · Programming Assistance · Computer Use |

---

## 一句话总结

面向 IDE 编程任务的主动 AI 助手研究：系统不等开发者开口，而是在代码上下文中主动给出帮助建议，并通过用户实验分析主动建议的收益、时机和打扰成本。

---

## 为什么适合本仓库

这篇论文的 proactive 不是泛泛的“更积极回复”，而是发生在真实 computer-use 场景中的主动介入：代理观察开发者当前代码与任务进展，判断是否应主动提出帮助。它直接回答了主动代理落地时最核心的问题之一：**什么时候帮忙会提高效率，什么时候会变成打扰**。

---

## 方法

- 构建主动式编程助手原型，嵌入 IDE/代码任务环境。
- 在 RealHumanEval 风格的编程任务中比较主动助手和被动助手。
- 分析主动建议的出现时机、建议粒度、用户接受度和任务完成效果。
- 通过用户研究收集开发者对主动帮助频率、可控性和信任边界的反馈。

---

## 核心结论

- 主动建议可以提升编程任务完成率，但收益高度依赖时机。
- 用户通常欢迎及时、上下文相关的帮助，但反感频繁或不合时宜的插入。
- 主动式 IDE 助手需要提供可控性，例如关闭、延后、调节频率或解释建议原因。

---

## 关键词

`Proactive Programming Assistant` · `IDE Agent` · `Computer Use` · `Intervention Timing` · `Human-AI Collaboration`
