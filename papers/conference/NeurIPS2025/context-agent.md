# ContextAgent: Context-Aware Proactive LLM Agents with Open-world Sensory Perceptions

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | NeurIPS 2025 |
| **作者** | Columbia ICSL（Intelligent and Connected Systems Lab） |
| **arXiv** | [arXiv:2505.14668](https://arxiv.org/abs/2505.14668) |
| **NeurIPS 主页** | [Poster #115593](https://neurips.cc/virtual/2025/poster/115593) |
| **领域** | cs.AI · cs.CL · cs.HC |

---

## 一句话总结

首个融合**可穿戴设备多模态感知**（视频、音频等）的主动 LLM 代理，突破了现有主动代理只能依赖桌面 UI 的局限，实现真实开放世界中的主动服务。

---

## 动机

现有主动代理存在两大缺陷：
1. **感知局限**：依赖封闭环境（如桌面 UI）的观察，无法感知用户的真实生活上下文。
2. **推理方式简单**：直接用 LLM 推断或基于规则触发通知，导致用户意图理解不准确。

真实世界的主动服务需要更丰富、更多样的上下文输入。

---

## 方法

### 三阶段框架

```
[多模态感知] → [上下文提取] → [主动性预测] → [服务执行]
  视频/音频/传感器      多维度上下文       是否需要主动？       工具调用
```

1. **多维度上下文提取**：从可穿戴设备的视频、音频等传感器流中提取多维语义上下文。
2. **历史 Persona 融合**：将传感器上下文与用户历史行为数据（persona context）结合，构建个性化的用户意图模型。
3. **主动性预测**：判断当前时刻是否需要主动服务（timing prediction）。
4. **工具调用执行**：确定需要主动介入后，规划并执行相应的工具调用序列。

---

## 核心优势

| 维度 | 先前工作 | ContextAgent |
|------|----------|-------------|
| 感知范围 | 桌面 UI（封闭） | 可穿戴多模态（开放世界） |
| 上下文丰富度 | 低 | 高（视频+音频+传感器） |
| 个性化 | 无 | 历史 persona 融合 |
| 主动时机判断 | 规则触发 | LLM 推理 |

---

## 核心结论

- ContextAgent 在主动服务预测和工具调用任务上显著超越基线
- 验证了开放世界感知对主动代理能力的关键作用
- 为可穿戴 AI 助手和边缘设备主动代理开辟了新方向

---

## 关键词

`Proactive Agent` · `Context-Aware` · `Wearable Sensing` · `Multi-modal Perception` · `Open-world` · `Tool Calling`
