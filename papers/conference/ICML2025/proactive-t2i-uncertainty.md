# Proactive Agents for Multi-Turn Text-to-Image Generation Under Uncertainty

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | ICML 2025 |
| **作者** | Zi Lin, Aleksander Madry, et al. |
| **arXiv** | [arXiv:2412.06771](https://arxiv.org/abs/2412.06771) |
| **OpenReview** | [f3iBgm2Zi0](https://openreview.net/forum?id=f3iBgm2Zi0) |
| **领域** | cs.AI · cs.CV · cs.LG |

---

## 一句话总结

将 Text-to-Image 生成从单轮猜测转变为**主动澄清的多轮对话**——当代理对用户意图不确定时，主动提问而非盲目生成。

---

## 动机

文本生成图像存在根本性的**意图对齐问题**：用户的文字描述往往模糊，模型被迫"猜测"，生成结果与用户真实期望往往有偏差。传统方案是让用户不断迭代 prompt，效率低下且用户体验差。

---

## 方法

### 核心框架：主动 T2I 代理

1. **不确定性感知**：代理对用户意图的不同解读维护概率分布，量化自身的不确定性。
2. **主动提问接口**：当不确定性超过阈值时，代理主动向用户提出**澄清问题**，而非强行生成。
3. **可编辑信念展示**：将代理当前对用户意图的理解（belief）以可视化、可直接编辑的形式呈现给用户，支持用户直接修正。
4. **多轮迭代生成**：结合用户反馈逐步精化生成结果。

---

## 核心创新

| 传统 T2I | 主动 T2I 代理 |
|----------|--------------|
| 单轮，被动接受 prompt | 多轮，主动澄清意图 |
| 模型内部猜测 | 不确定性显式建模 |
| 用户迭代 prompt | 代理主动提问 |
| 黑盒生成 | belief 可视化可编辑 |

---

## 核心结论

- 主动澄清机制显著提升用户意图对齐率
- 可编辑 belief 界面降低了用户修正成本
- 验证了"不确定性驱动的主动行为"在创意生成任务中的价值

---

## 关键词

`Proactive Agent` · `Text-to-Image` · `Uncertainty` · `Clarification Questions` · `Multi-Turn` · `Human-AI Alignment`
