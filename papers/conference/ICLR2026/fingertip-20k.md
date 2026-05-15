# FingerTip 20K: A Benchmark for Proactive and Personalized Mobile LLM Agents

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | ICLR 2026 Poster |
| **arXiv ID** | [arXiv:2507.21071](https://arxiv.org/abs/2507.21071) |
| **首发日期** | 2025 年 6 月 |
| **代码** | [GitHub](https://github.com/tsinghua-fib-lab/FingerTip-20K) |
| **领域** | Mobile GUI Agent · Personalization · Benchmark |

---

## 一句话总结

面向移动 GUI 的主动与个性化代理基准：基于真实长期手机使用轨迹，评测代理能否主动建议任务，并按用户偏好执行移动端多步操作。

---

## 为什么适合本仓库

FingerTip 20K 把 mobile GUI agent 从“执行显式指令”推进到“根据上下文和历史行为主动建议任务”。它同时强调主动建议和个性化执行，是 GUI/Mobile proactive agent 主线中的关键数据集。

---

## Benchmark 设计

| 维度 | 内容 |
|------|------|
| **数据来源** | 长期真实 Android 使用记录 |
| **规模** | 约 20K human demonstrations |
| **应用覆盖** | 多个日常移动应用 |
| **任务轨道** | 主动任务建议 · 个性化任务执行 |
| **上下文信号** | 时间、位置、用户画像、历史意图、GUI 轨迹 |

---

## 核心任务

1. **Proactive Task Suggestion**：根据环境观测和用户历史意图，判断此刻是否应建议某个任务。
2. **Personalized Task Execution**：在执行同一目标时，生成符合用户习惯的移动 GUI 操作轨迹。

---

## 核心结论

- 当前移动 GUI agent 对用户相关上下文的利用仍然很弱。
- 主动建议和个性化执行都需要长期历史，而不是单次截图或单条指令。
- 用真实用户轨迹训练的模型能更好利用用户信息，但距离人类表现仍有明显差距。

---

## 关键词

`Mobile GUI Agent` · `Proactive Task Suggestion` · `Personalization` · `Long-term User History` · `Android Agent`
