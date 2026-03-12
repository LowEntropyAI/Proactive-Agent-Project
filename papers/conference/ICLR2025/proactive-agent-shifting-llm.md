# Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | ICLR 2025 |
| **作者** | Yaxi Lu, Shenzhi Yang, Zecheng Tang, Guanxin Dai, Tao Gui, Qi Zhang, Xuanjing Huang |
| **单位** | Fudan University |
| **arXiv** | — |
| **OpenReview** | [sRIU6k2TcU](https://openreview.net/forum?id=sRIU6k2TcU) |
| **ICLR 主页** | [Poster #28128](https://iclr.cc/virtual/2025/poster/28128) |

---

## 一句话总结

构建并评测了首个**数据驱动的主动代理框架**，通过观察用户桌面行为来预测并主动发起任务，无需等待显式指令。

---

## 动机

现有 LLM 代理系统几乎全部基于**被动（Reactive）范式**：只有用户明确发出指令，代理才会行动。这在需要**预见性与自主决策**的场景下严重限制了代理的有效性。

---

## 方法

1. **数据收集**：收集真实世界用户的桌面活动数据，涵盖屏幕状态、操作序列等上下文信号。
2. **任务预测生成**：将用户活动数据转化为主动任务预测样本，标注"用户可能下一步希望代理做什么"。
3. **奖励模型训练（ProactiveBench）**：训练一个模拟人类判断的奖励模型，作为主动性的自动评估器。
4. **SFT 微调**：使用 ProactiveBench 对 LLM 进行监督微调，显著提升模型的主动性表现。

---

## ProactiveBench

- **任务定义**：给定用户当前活动序列 → 预测用户接下来可能希望代理执行的任务
- **评估维度**：主动任务预测的准确性、相关性、实用性
- **自动评估**：奖励模型替代人工标注，实现可扩展评测

---

## 核心结论

- 经过 ProactiveBench 微调的模型在主动性上显著优于基线 LLM
- 验证了"主动性"是可学习的能力，而非模型固有属性
- 为未来更主动、更高效的人机协作系统铺平了道路

---

## 关键词

`Proactive Agent` · `Task Anticipation` · `Human-Agent Collaboration` · `Reward Model` · `Desktop Activity`
