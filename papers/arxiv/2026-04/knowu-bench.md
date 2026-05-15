# KnowU-Bench: Towards Interactive, Proactive, and Personalized Mobile Agent Evaluation

## 基本信息

| 字段 | 内容 |
|------|------|
| **来源** | arXiv preprint |
| **arXiv ID** | [arXiv:2604.08455](https://arxiv.org/abs/2604.08455) |
| **首发日期** | 2026 年 4 月 9 日 |
| **领域** | Mobile Agent · Personalization · Proactive Evaluation |

---

## 一句话总结

Android 移动代理在线评测基准，统一考察 GUI 执行、个性化偏好推断、主动介入、同意管理和被拒后的克制能力。

---

## 为什么适合本仓库

KnowU-Bench 是最贴近“可部署 proactive personal mobile assistant”的工作之一。它不仅问代理会不会执行 GUI 任务，还问代理能否在不知道用户画像的情况下从行为日志推断偏好，主动澄清、请求同意，并在用户拒绝后停止越界行为。

---

## Benchmark 设计

| 维度 | 内容 |
|------|------|
| **环境** | 可复现 Android emulation environment |
| **任务类型** | general GUI tasks · personalized tasks · proactive tasks |
| **任务规模** | 42 general tasks · 86 personalized tasks · 64 proactive tasks |
| **用户信息** | 隐藏结构化画像，只暴露行为日志 |
| **交互机制** | LLM user simulator 支持澄清、同意和拒绝 |

---

## 核心问题

1. 代理能否从行为日志中恢复用户偏好，而不是直接读取画像。
2. 代理能否在需要时主动介入，在不需要时保持沉默。
3. 代理能否正确请求同意，并在用户拒绝后克制后续行动。
4. 主动性错误究竟来自 GUI 导航，还是来自偏好推断和介入校准。

---

## 关键词

`Mobile Agent` · `Proactive Assistance` · `Personalization` · `Consent Management` · `Android GUI`
