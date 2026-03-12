# 🤖 Proactive Agent Project

> A curated reading list of research papers on **Proactive Agents** — AI agents that autonomously anticipate user needs, initiate tasks, and act without waiting for explicit instructions.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/LowEntropyAI/Proactive-Agent-Project/pulls)

---

## 📖 Table of Contents

- [What is a Proactive Agent?](#what-is-a-proactive-agent)
- [Paper Index](#paper-index)
  - [Top Conference Papers](#top-conference-papers)
  - [Recent arXiv Papers](#recent-arxiv-papers)
- [Benchmark Comparison](#benchmark-comparison)
- [Contributing](#contributing)

---

## What is a Proactive Agent?

A **Proactive Agent** is an AI system that goes beyond passive, instruction-following behavior. Instead of waiting for explicit user commands, it:

- 🔮 **Anticipates** user intentions from contextual signals (screen activity, sensors, conversation history)
- 🚀 **Initiates** tasks autonomously before being asked
- ❓ **Clarifies** ambiguous goals through targeted questions
- 🔁 **Adapts** to long-term user preferences and patterns

This is in contrast to the dominant **reactive paradigm**, where agents only act in response to direct user instructions.

---

## Paper Index

### Top Conference Papers

#### ICLR 2025

| Title | Authors | Paper Notes | Links |
|-------|---------|-------------|-------|
| **Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance** | Yaxi Lu, Shenzhi Yang et al. (Fudan Univ.) | [📄 Notes](papers/conference/ICLR2025/proactive-agent-shifting-llm.md) | [OpenReview](https://openreview.net/forum?id=sRIU6k2TcU) · [ICLR](https://iclr.cc/virtual/2025/poster/28128) |

> Proposes the first data-driven framework for building proactive agents that predict and initiate user tasks without explicit instructions. Introduces **ProactiveBench** — a reward model trained to simulate human judgment of proactiveness, used for fine-tuning LLMs to be significantly more proactive.

---

#### ICML 2025

| Title | Authors | Paper Notes | Links |
|-------|---------|-------------|-------|
| **Proactive Agents for Multi-Turn Text-to-Image Generation Under Uncertainty** | Zi Lin, Aleksander Madry et al. | [📄 Notes](papers/conference/ICML2025/proactive-t2i-uncertainty.md) | [arXiv:2412.06771](https://arxiv.org/abs/2412.06771) · [OpenReview](https://openreview.net/forum?id=f3iBgm2Zi0) |

> Studies the alignment problem in T2I generation. Introduces proactive T2I agents that actively ask clarification questions when uncertain about user intent, and present their uncertainty beliefs as an editable interface. Transforms image generation from one-shot guessing into collaborative multi-turn dialogue.

---

#### NeurIPS 2025

| Title | Authors | Paper Notes | Links |
|-------|---------|-------------|-------|
| **ContextAgent: Context-Aware Proactive LLM Agents with Open-world Sensory Perceptions** | Columbia ICSL | [📄 Notes](papers/conference/NeurIPS2025/context-agent.md) | [arXiv:2505.14668](https://arxiv.org/abs/2505.14668) · [NeurIPS](https://neurips.cc/virtual/2025/poster/115593) |

> Introduces the first proactive agent that fuses multi-dimensional sensory contexts from wearables (video, audio, etc.) to predict when and how to proactively assist users in open-world scenarios. Outperforms all baselines on proactive service prediction and tool-calling tasks.

---

#### AAMAS 2025

| Title | Authors | Paper Notes | Links |
|-------|---------|-------------|-------|
| **The Next Level of Long-Term Agent Autonomy — Proactively Learning New Knowledge and Abilities** | Hermine J. EP et al. | [📄 Notes](papers/conference/AAMAS2025/proactive-long-term-autonomy.md) | [PDF](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p2859.pdf) |

> Elevates proactivity to a meta-level: agents that autonomously decide *what new knowledge and abilities to acquire*. Frames this via epistemic reasoning and qualitative learning. Highlights critical ethical challenges when agents can self-direct their own learning.

---

### Recent arXiv Papers

#### January 2025

| Title | Date | Paper Notes | arXiv |
|-------|------|-------------|-------|
| **Proactive Conversational Agents with Inner Thoughts** | Jan 1, 2025 | [📄 Notes](papers/arxiv/2025-01/proactive-conversational-inner-thoughts.md) | [2501.00383](https://arxiv.org/abs/2501.00383) |
| **YETI (YET to Intervene): Proactive Interventions by Multimodal AI Agents in AR** | Jan 16, 2025 | [📄 Notes](papers/arxiv/2025-01/yeti-proactive-ar-intervention.md) | [2501.09355](https://arxiv.org/abs/2501.09355) |

**Proactive Conversational Agents with Inner Thoughts** (`2501.00383`)
> Introduces an *inner thought* mechanism that tracks latent user states and goals across conversation turns, enabling agents to proactively steer dialogues — asking follow-up questions or suggesting next steps without waiting for explicit requests.

**YETI: Proactive Interventions by Multimodal AI Agents in AR** (`2501.09355`)
> A multimodal agent framework for Augmented Reality that monitors users through multi-sensor perception and proactively intervenes at the right moment. Addresses the core challenge of *when* to intervene without being intrusive.

---

#### February 2025

| Title | Date | Paper Notes | arXiv |
|-------|------|-------------|-------|
| **ProAgentBench: Evaluating LLM Agents for Proactive Assistance with Real-World Data** | Feb 6, 2025 | [📄 Notes](papers/arxiv/2025-02/proagentbench.md) | [2602.04482](https://arxiv.org/abs/2602.04482) |
| **ProactiveMobile: A Comprehensive Benchmark for Boosting Proactive Intelligence on Mobile Devices** | Feb 28, 2025 | [📄 Notes](papers/arxiv/2025-02/proactivemobile.md) | [2602.21858](https://arxiv.org/abs/2602.21858) |

**ProAgentBench** (`2602.04482`)
> The first rigorous benchmark using real-world data to evaluate proactive agents in continuous environments. Reveals that current LLMs tend to either over-trigger or never proactively assist — timing judgment is harder than content generation.

**ProactiveMobile** (`2602.21858`)
> Comprehensive mobile proactive intelligence benchmark: 3,660+ instances across 14 scenarios, 63 APIs. Key finding: fine-tuned 7B Qwen2.5-VL (19.15%) beats o1 (15.71%) and GPT-5 (7.39%), proving proactivity is a *learnable* specialized skill.

---

#### October–December 2024 (Strong Preprints)

| Title | Date | Paper Notes | arXiv |
|-------|------|-------------|-------|
| **Measuring Proactive Problem Solving in LLM Agents** | Oct 2024 | [📄 Notes](papers/arxiv/2024-10-12/measuring-proactive-problem-solving.md) | [2510.19771](https://arxiv.org/abs/2510.19771) |
| **RoboOmni: Proactive Robot Manipulation in Omni-modal Context** | Oct 2024 | [📄 Notes](papers/arxiv/2024-10-12/roboomni-proactive-manipulation.md) | [2510.23763](https://arxiv.org/abs/2510.23763) |
| **ProAgent: Harnessing On-Demand Sensory Contexts for Proactive LLM Agent Systems** | Dec 2024 | [📄 Notes](papers/arxiv/2024-10-12/proagent-on-demand-sensing.md) | [2512.06721](https://arxiv.org/abs/2512.06721) |
| **SmartSnap: Proactive Evidence Seeking for Self-Verifying Agents** | Dec 2024 | [📄 Notes](papers/arxiv/2024-10-12/smartsnap-self-verifying.md) | [2512.22322](https://arxiv.org/abs/2512.22322) |

**Measuring Proactive Problem Solving** (`2510.19771`)
> Benchmark where agents must proactively discover and resolve user *bottlenecks* without being told what the problems are. Tests GPT-5, Claude 4.1 Opus, Kimi-K2, DeepSeek-R1 and others.

**RoboOmni** (`2510.23763`)
> Proactive robot manipulation system fusing text/vision/audio. Features proactive clarification: when instructions are ambiguous, the robot asks targeted questions instead of guessing.

**ProAgent (On-Demand Sensing)** (`2512.06721`)
> Proposes on-demand sensing for proactive agents — the agent dynamically decides *which sensors to query* based on current uncertainty, enabling edge-device deployment.

**SmartSnap** (`2512.22322`)
> Introduces the Self-Verifying Agent: agents that proactively collect screenshot evidence *during* task execution to prove completion. Formalizes this as an augmented MDP.

---

## Benchmark Comparison

| Benchmark | Paper | Venue | Focus | Scale |
|-----------|-------|-------|-------|-------|
| **ProactiveBench** | Proactive Agent | ICLR 2025 | Desktop activity → task prediction | Real-world human activities |
| **ProAgentBench** | arXiv:2602.04482 | arXiv 2025 | Real-world proactive assistance | Continuous environment |
| **ProactiveMobile** | arXiv:2602.21858 | arXiv 2025 | Mobile device proactive intelligence | 3,660+ instances, 14 scenarios |
| **YETI Benchmark** | arXiv:2501.09355 | arXiv 2025 | AR proactive intervention timing | Multimodal AR tasks |

---

## Contributing

We welcome contributions! If you know of a relevant paper:

1. **Fork** this repo
2. **Add a paper note** in the appropriate `papers/` subdirectory (use existing files as template)
3. **Update** the table in `README.md`
4. **Submit** a pull request

**Paper note template:**
```markdown
# Paper Title

## 基本信息
| 字段 | 内容 |
|------|------|
| **会议/来源** | ... |
| **arXiv ID** | [arXiv:XXXX.XXXXX](https://arxiv.org/abs/XXXX.XXXXX) |

## 一句话总结
...

## 动机
...

## 方法
...

## 核心结论
...

## 关键词
`Proactive Agent` · ...
```

---

<p align="center">
  Maintained by <a href="https://github.com/LowEntropyAI">Low Entropy AI</a> · Star ⭐ if you find this useful!
</p>
