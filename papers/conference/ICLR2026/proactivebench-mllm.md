# ProactiveBench: Benchmarking Proactiveness in Multimodal Large Language Models

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | ICLR 2026 |
| **arXiv ID** | [arXiv:2603.19466](https://arxiv.org/abs/2603.19466) |
| **作者** | Thomas Demin et al. (University of Trento) |
| **代码/数据** | [github.com/tdemin16/proactivebench](https://github.com/tdemin16/proactivebench) · [HuggingFace Dataset](https://huggingface.co/datasets/tdemin16/ProactiveBench) |
| **领域** | cs.CV · cs.AI · Multimodal LLM |

---

## ⚠️ 命名说明

> 本文与 ICLR 2025 中的 **ProactiveBench**（Yaxi Lu et al., Fudan University）同名但完全独立：
> - **ICLR 2025 ProactiveBench**：桌面行为数据驱动，评测 LLM 主动预测用户下一个任务的能力
> - **本文（ICLR 2026 ProactiveBench）**：视觉场景驱动，评测 MLLM 在视觉困难情况下主动寻求帮助的能力

---

## 一句话总结

首个评测**多模态大模型（MLLM）主动性**的视觉基准：当图像中对象被遮挡或图像质量差时，模型是否能像人类一样主动请求用户帮助？

---

## 核心问题

"有效的协作始于知道何时寻求帮助。当人类面对被遮挡的物体时，会主动请别人移开障碍物。MLLM 能展现这种主动行为吗？"

---

## Benchmark 设计

| 要素 | 内容 |
|------|------|
| **数据来源** | 7 个现有数据集重新目的化 |
| **评测任务** | 识别被遮挡对象、提升图像质量、理解粗糙草图等 |
| **评测对象** | 22 个主流 MLLM |
| **核心指标** | 模型是否在视觉困难时主动发起帮助请求 |

### 任务类型

```
视觉困难场景（遮挡/低质量/模糊草图）
    ↓
理想主动行为：模型主动请求用户提供更好的视图/信息
    ↓
评测：主动率、误触发率、干预质量
```

---

## 核心发现

| 发现 | 结论 |
|------|------|
| **主流 MLLM 普遍缺乏主动性** | 22 个模型评测均表现不佳 |
| **主动性不随模型规模增长** | 大模型并不比小模型更主动 |
| **"提示"主动性效果有限** | 告诉模型"可以请求帮助"仅带来微小提升 |
| **对话历史引入负偏差** | 多轮对话上下文反而抑制主动行为 |
| **RL 微调有效** | 强化学习微调可以学会主动性，且可泛化至未见场景 |

---

## 核心贡献

1. 首个系统评测 MLLM 视觉主动性的公开基准
2. 揭示当前模型在主动行为上的系统性缺失
3. 证明主动性可通过 RL 微调学得，且具备跨场景泛化能力
4. 提供完全开放的数据集和评测框架

---

## 与项目的关联

本文是本项目**"GUI/Mobile/OS Proactive Agents"**类别中关于**基准评测**的重要补充：
- 将"主动性"从任务预测扩展到视觉感知层面
- 揭示了当前主流 MLLM 在主动行为上的根本缺口
- RL 微调方向与主动代理能力培养高度相关

---

## 关键词

`Proactive Agent` · `MLLM Benchmark` · `Visual Proactiveness` · `Multimodal LLM` · `Human-AI Collaboration` · `Reinforcement Learning` · `ICLR 2026`
