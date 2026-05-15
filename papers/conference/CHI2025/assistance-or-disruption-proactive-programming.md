# Assistance or Disruption? Exploring and Evaluating the Design and Trade-offs of Proactive AI Programming Support

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议/来源** | CHI 2025 |
| **arXiv ID** | [arXiv:2502.18658](https://arxiv.org/abs/2502.18658) |
| **首发日期** | 2025 年 2 月 25 日 |
| **DOI** | [10.1145/3706598.3713357](https://doi.org/10.1145/3706598.3713357) |
| **领域** | Proactive Programming Support · Human-AI Interaction · IDE |

---

## 一句话总结

系统研究主动式编程支持的收益与打扰成本：主动建议可以帮助开发者，但过早、过频或不合上下文的介入会破坏工作流。

---

## 为什么适合本仓库

这篇论文直接研究 proactive coding assistant 的核心部署问题：主动支持到底是 assistance 还是 disruption。它适合作为 IDE/computer-use proactive agent 的人因边界论文，帮助避免只用任务成功率评价主动系统。

---

## 研究重点

- 设计并评估 Codellaborator，一个根据 editor activity 和 task context 主动发起帮助的 LLM design probe。
- 对比 prompt-only、proactive agent、proactive agent with presence/context 三种界面变体。
- 在 N=18 的 within-subject study 中分析主动式 AI 编程支持在什么情况下能提高效率。
- 开发者如何感知主动建议的时机、频率和控制权。
- 主动建议如何影响认知负荷、工作流连续性和用户接受度。

---

## 核心结论

- 主动支持不是越多越好，低质量或不合时机的建议会显著打断开发者。
- 主动式 IDE 助手需要可调节的频率、可解释的触发原因和清晰的关闭机制。
- 评测 proactive programming assistant 时，应同时记录效率收益和 interruption cost。

---

## 关键词

`Proactive Programming Support` · `IDE Assistant` · `Interruption Cost` · `Human Factors` · `Developer Experience`
