# An Empirical Study of Proactive Coding Assistants in Real-World Software Development

## 基本信息

| 字段 | 内容 |
|------|------|
| **来源** | arXiv preprint |
| **arXiv ID** | [arXiv:2605.05700](https://arxiv.org/abs/2605.05700) |
| **首发日期** | 2026 年 5 月 |
| **基准** | ProCodeBench |
| **领域** | Coding Agent · IDE Trajectory · Real-world Evaluation |

---

## 一句话总结

基于真实 IDE 使用轨迹的主动编程助手实证研究，揭示模拟轨迹与真实开发行为之间的 sim-to-real 差距，并提出 ProCodeBench。

---

## 为什么适合本仓库

主动 coding assistant 是 computer-use proactive agent 的重要分支。这篇论文的价值在于它使用真实开发者 IDE 轨迹，而不是只依赖 synthetic traces，因此能更准确暴露主动建议在真实软件开发中的时机、内容和行为偏差。

---

## 研究设计

- 通过 VS Code 扩展采集真实开发者多天 IDE 交互轨迹。
- 对比真实轨迹和 LLM 模拟轨迹在多样性、时间结构、探索路径上的差异。
- 构建 ProCodeBench，用于评测主动编程助手在真实开发上下文中的能力。

---

## 核心结论

- 模拟轨迹会系统性低估真实开发行为的复杂性。
- 真实开发者行为包含更多探索、反复修改、停顿和上下文切换。
- 仅在 synthetic traces 上评测 proactive coding assistant，容易高估实际部署表现。

---

## 关键词

`Proactive Coding Assistant` · `IDE Agent` · `Real-world Trajectory` · `ProCodeBench` · `Sim-to-real Gap`
