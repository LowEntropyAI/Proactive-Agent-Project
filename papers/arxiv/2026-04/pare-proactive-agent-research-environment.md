# Proactive Agent Research Environment: Simulating Active Users to Evaluate Proactive Assistants

## 基本信息

| 字段 | 内容 |
|------|------|
| **来源** | arXiv preprint |
| **简称** | Pare / Pare-Bench |
| **arXiv ID** | [arXiv:2604.00842](https://arxiv.org/abs/2604.00842) |
| **首发日期** | 2026 年 4 月 1 日 |
| **领域** | Digital Environment · User Simulation · Proactive Assistant Evaluation |

---

## 一句话总结

提出用于评测主动数字助手的状态化研究环境：把应用建模为有限状态机，模拟活跃用户与主动助手之间的闭环协作。

---

## 为什么适合本仓库

Pare 的贡献在于纠正“把应用当作扁平 API 集合”的过度简化。主动助手必须面对用户正在导航、任务状态不断变化、多应用目标交织的环境，因此 Pare-Bench 对 GUI/OS/computer-use proactive agent 有直接价值。

---

## Benchmark 设计

| 维度 | 内容 |
|------|------|
| **环境建模** | 应用被建模为 finite state machines |
| **用户模拟** | 用户按状态化界面逐步导航 |
| **助手能力** | 观察上下文、推断目标、选择介入时机、执行后端动作 |
| **任务规模** | 143 个任务 |
| **覆盖场景** | communication · productivity · scheduling · lifestyle |

---

## 核心评测能力

- Context observation：能否理解用户当前状态。
- Goal inference：能否推断用户隐含目标。
- Intervention timing：能否在合适时机介入。
- Multi-app orchestration：能否跨多个应用完成主动帮助。

---

## 关键词

`Proactive Assistant` · `User Simulation` · `Finite State Machine` · `Digital Environment` · `Multi-app Agent`
