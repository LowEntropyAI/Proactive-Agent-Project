# PIRA-Bench: A Transition from Reactive GUI Agents to GUI-based Proactive Intent Recommendation Agents

## 基本信息

| 字段 | 内容 |
|------|------|
| **来源** | arXiv preprint |
| **arXiv ID** | [arXiv:2603.08013](https://arxiv.org/abs/2603.08013) |
| **首发日期** | 2026 年 3 月 9 日 |
| **领域** | GUI Agent · Proactive Intent Recommendation · MLLM Benchmark |

---

## 一句话总结

GUI 主动意图推荐基准：代理需要从连续截图流、噪声操作和多任务切换中识别用户潜在意图，并在合适时机给出主动推荐。

---

## 为什么适合本仓库

PIRA-Bench 直接针对 reactive GUI agent 的局限：传统 GUI agent 等待显式指令，而这里的代理必须从连续视觉上下文中发现值得推荐的潜在任务。它是 GUI proactive agent 主线的核心 benchmark。

---

## Benchmark 设计

- 使用连续 GUI 轨迹，而不是单张截图或单步任务。
- 轨迹中包含噪声浏览、无意义操作、多线程任务切换和用户画像上下文。
- 评测目标是检测 actionable events，并生成符合用户偏好的意图推荐。
- 提出 PIRF baseline，通过动态记忆和状态跟踪管理多条任务线索。

---

## 核心挑战

1. **何时推荐**：必须识别真正值得介入的时刻。
2. **何时沉默**：噪声操作和低价值事件不应触发建议。
3. **多意图管理**：真实屏幕活动常常包含多个交织任务。
4. **个性化匹配**：同一 GUI 行为对不同用户可能有不同含义。

---

## 关键词

`GUI Agent` · `Proactive Intent Recommendation` · `Continuous Screenshots` · `User Intent` · `MLLM Benchmark`
