# VeriOS: Query-Driven Proactive Human-Agent-GUI Interaction for Trustworthy OS Agents

## 基本信息

| 字段 | 内容 |
|------|------|
| **来源** | arXiv preprint |
| **arXiv ID** | [arXiv:2509.07553](https://arxiv.org/abs/2509.07553) |
| **首发日期** | 2025 年 9 月 9 日 |
| **代码/数据/模型** | [GitHub](https://github.com/Wuzheng02/VeriOS) |
| **领域** | OS Agent · GUI Agent · Trustworthy Agent |

---

## 一句话总结

面向不可信 OS/GUI 环境的主动问询框架：代理在正常条件下自动执行，在风险或不可信场景中主动向人类查询，从而降低过度执行风险。

---

## 为什么适合本仓库

VeriOS 的主动性核心是 **query-driven intervention**：代理必须判断“继续执行还是主动问人”。这不是一般 GUI 执行论文，而是把 proactive 行为放在 OS agent 的信任校准与权限边界中研究。

---

## 方法

- 构建 human-agent-GUI 交互框架，使 OS agent 在不可信条件下主动查询用户。
- 训练 VeriOS-Agent，使其区分正常场景和需要人类确认的风险场景。
- 采用三阶段训练范式，将 meta-knowledge、SFT 与 GRPO 结合到 GUI 决策中。

---

## 核心结论

- 主动查询能显著改善不可信场景下的 step-wise success rate。
- 在可信场景中，代理仍能保持接近自动执行的效率。
- 对 OS agent 而言，proactivity 不只是“主动帮忙”，也包括**主动请求确认、主动限制自治**。

---

## 关键词

`OS Agent` · `GUI Agent` · `Proactive Querying` · `Trust Calibration` · `Human-in-the-loop`
