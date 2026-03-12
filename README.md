# 🤖 Proactive Agent Project

> A curated reading list of research papers on **Proactive Agents** — AI agents that autonomously anticipate user needs, initiate tasks, and act without waiting for explicit instructions.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/LowEntropyAI/Proactive-Agent-Project/pulls)

---

## 📖 Table of Contents

- [What is a Proactive Agent?](#what-is-a-proactive-agent)
- [Top Conference Papers](#top-conference-papers)
- [Recent arXiv Papers](#recent-arxiv-papers)
- [Related Benchmarks](#related-benchmarks)
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

## Top Conference Papers

### ICLR 2025

| Title | Authors | Links |
|-------|---------|-------|
| **Proactive Agent: Shifting LLM Agents from Reactive Responses to Active Assistance** | Yaxi Lu, Shenzhi Yang, et al. | [OpenReview](https://openreview.net/forum?id=sRIU6k2TcU) · [ICLR](https://iclr.cc/virtual/2025/poster/28128) |

> **TL;DR:** Proposes the first data-driven framework for building proactive agents that predict and initiate user tasks without explicit instructions. Collects real-world human desktop activities, trains a reward model simulating human judgment (**ProactiveBench**), and fine-tunes LLMs to significantly boost proactiveness. Highlights the path toward genuinely proactive human-agent collaboration.

---

### ICML 2025

| Title | Authors | Links |
|-------|---------|-------|
| **Proactive Agents for Multi-Turn Text-to-Image Generation Under Uncertainty** | Zi Lin, Aleksander Madry, et al. | [arXiv:2412.06771](https://arxiv.org/abs/2412.06771) · [OpenReview](https://openreview.net/forum?id=f3iBgm2Zi0) |

> **TL;DR:** Studies the alignment problem in text-to-image generation by introducing proactive T2I agents that actively ask clarification questions when uncertain about user intent, and present their uncertainty beliefs in an editable interface. Moves T2I generation from a one-shot guessing game to a collaborative, iterative dialogue.

---

### NeurIPS 2025

| Title | Authors | Links |
|-------|---------|-------|
| **ContextAgent: Context-Aware Proactive LLM Agents with Open-world Sensory Perceptions** | Columbia ICSL | [arXiv:2505.14668](https://arxiv.org/abs/2505.14668) · [NeurIPS](https://neurips.cc/virtual/2025/poster/115593) |

> **TL;DR:** Introduces ContextAgent, the first proactive agent that fuses multi-dimensional sensory contexts from wearables (video, audio, etc.) to predict when and how to proactively assist users. Unlike prior agents confined to desktop UIs, ContextAgent operates in open-world scenarios. Demonstrates strong performance on proactive service prediction and tool-calling tasks.

---

### AAMAS 2025

| Title | Authors | Links |
|-------|---------|-------|
| **The Next Level of Long-Term Agent Autonomy — Proactively Learning New Knowledge and Abilities** | Hermine J. EP et al. | [PDF](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p2859.pdf) |

> **TL;DR:** Explores a new research direction where agents proactively decide what new knowledge and abilities to acquire, framed via epistemic reasoning and policy learning. Highlights ethical challenges of agents with high autonomy that can self-direct their own learning — a critical open problem for long-term agentic AI systems.

---

## Recent arXiv Papers

### 2025 — January

| Title | Date | Links |
|-------|------|-------|
| **Proactive Conversational Agents with Inner Thoughts** | Jan 1, 2025 | [arXiv:2501.00383](https://arxiv.org/abs/2501.00383) |
| **YETI (YET to Intervene): Proactive Interventions by Multimodal AI Agents in Augmented Reality** | Jan 16, 2025 | [arXiv:2501.09355](https://arxiv.org/abs/2501.09355) |

#### Proactive Conversational Agents with Inner Thoughts `2501.00383`
> Proposes a conversational agent with an **inner thought** mechanism that tracks latent user states and goals across turns, enabling the agent to proactively steer conversations — asking follow-up questions or suggesting next steps — without waiting for the user to explicitly request them. Addresses cs.HC and cs.AI.

#### YETI: Proactive Interventions by Multimodal AI Agents in AR `2501.09355`
> Introduces YETI, a multimodal agent framework for **Augmented Reality** environments that proactively intervenes to assist users in day-to-day tasks. The agent monitors the user's context through multimodal perception and decides when to proactively deliver information or guidance, rather than waiting to be summoned.

---

### 2025 — February

| Title | Date | Links |
|-------|------|-------|
| **ProAgentBench: Evaluating LLM Agents for Proactive Assistance with Real-World Data** | Feb 6, 2025 | [arXiv:2602.04482](https://arxiv.org/abs/2602.04482) |
| **ProactiveMobile: A Comprehensive Benchmark for Boosting Proactive Intelligence on Mobile Devices** | Feb 28, 2025 | [arXiv:2602.21858](https://arxiv.org/abs/2602.21858) |

#### ProAgentBench `2602.04482`
> The first rigorous benchmark for evaluating proactive agents within continuous real-world environments. Provides structured evaluation across tasks where agents must decide *when* and *how* to proactively assist users, going beyond passive task completion.

#### ProactiveMobile `2602.21858`
> A comprehensive benchmark for proactive intelligence on mobile devices. Formalizes proactive tasks as inferring **latent user intent** across 4 dimensions of on-device contextual signals, with 3,660+ instances spanning 14 real-world scenarios and 63 API functions. Fine-tuned Qwen2.5-VL-7B outperforms o1 and GPT-5 in success rate (19.15% vs 15.71%), highlighting proactivity as a learnable but currently lacking competency in MLLMs.

---

### 2024 — December (Accepted to 2025 Conferences / Strong Preprints)

| Title | Date | Links |
|-------|------|-------|
| **ProAgent: Harnessing On-Demand Sensory Contexts for Proactive LLM Agent Systems** | Dec 2024 | [arXiv:2512.06721](https://arxiv.org/abs/2512.06721) |
| **SmartSnap: Proactive Evidence Seeking for Self-Verifying Agents** | Dec 2024 | [arXiv:2512.22322](https://arxiv.org/abs/2512.22322) |

#### ProAgent `2512.06721`
> Explores **on-demand sensory context** acquisition for proactive agents — rather than always ingesting all sensor streams, the agent decides which sensory inputs to query based on its current uncertainty. Addresses edge-platform deployment constraints for proactive LLM systems.

#### SmartSnap `2512.22322`
> Introduces the **Self-Verifying Agent**: an agent that proactively seeks snapshot evidence to *prove* task completion, formalizing this as an augmented MDP. Reframes verification from passive post-hoc analysis to an active, proactive process integrated into task execution.

---

### 2024 — October

| Title | Date | Links |
|-------|------|-------|
| **Measuring Proactive Problem Solving in LLM Agents** | Oct 2024 | [arXiv:2510.19771](https://arxiv.org/abs/2510.19771) |
| **RoboOmni: Proactive Robot Manipulation in Omni-modal Context** | Oct 2024 | [arXiv:2510.23763](https://arxiv.org/abs/2510.23763) |

#### Measuring Proactive Problem Solving `2510.19771`
> Proposes a benchmark where agents are given user priorities and a personal datastore, then must **proactively identify and resolve bottlenecks** without being told what the problems are. Evaluates GPT-4.1, Claude Opus, Kimi-K2, DeepSeek-R1 and others.

#### RoboOmni `2510.23763`
> A proactive robotic manipulation system in omni-modal context (text, audio, vision). Features **proactive clarification** — when facing ambiguous instructions, the robot asks targeted questions rather than guessing, combined with rich multimodal scene understanding.

---

## Related Benchmarks

| Benchmark | Paper | Focus |
|-----------|-------|-------|
| **ProactiveBench** | Proactive Agent (ICLR 2025) | Desktop activity-based proactive task prediction |
| **ProAgentBench** | arXiv:2602.04482 | Real-world proactive assistance evaluation |
| **ProactiveMobile** | arXiv:2602.21858 | Mobile device proactive intelligence, 63 APIs |
| **AR-Bench** | ICML 2025 (AR-Bench) | Active reasoning in agentic scenarios |

---

## Contributing

We welcome contributions! If you know of a relevant paper that belongs here:

1. Fork the repo
2. Add the paper to the appropriate section in `README.md`
3. Submit a pull request

**Format:**
```
| **Paper Title** | Authors | [arXiv:XXXX.XXXXX](link) |
```
With a 1–2 sentence summary in the block quote below.

---

<p align="center">
  Maintained by <a href="https://github.com/LowEntropyAI">Low Entropy AI</a> · Star ⭐ if you find this useful!
</p>
