# The Next Level of Long-Term Agent Autonomy — Proactively Learning New Knowledge and Abilities

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | AAMAS 2025 |
| **作者** | Hermine J. EP et al. |
| **PDF** | [AAMAS Proceedings](https://www.ifaamas.org/Proceedings/aamas2025/pdfs/p2859.pdf) |
| **关键词** | Proactivity · Autonomy · Human-AI Systems · Long-term Agents · Epistemic Reasoning |

---

## 一句话总结

提出代理**主动决定学习什么知识与能力**的新研究方向，将主动性推进到"元学习层面"——代理不只是主动做任务，而是主动规划自身的成长。

---

## 动机

现有主动代理研究多聚焦于"主动做事"（anticipating tasks），但忽视了一个更深层的主动性：  
**代理是否能主动识别自身的知识/能力缺口，并决定去学习填补？**

这种"元层面主动性"对实现真正长期自主代理至关重要。

---

## 方法与框架

### 认识论策略（Epistemic Policy）

- 形式化代理的**认识论目标**（Epistemic Goal）：代理需要知道哪些事情才能完成任务
- 通过**能力推理**（Ability Reasoning）识别代理当前不具备的行动模型
- 通过**定性学习**（Qualitative Learning）确定需要从观测流或外部公告中获取的知识

### 主动学习循环

```
[识别知识缺口] → [规划学习策略] → [主动获取知识/能力] → [更新行动模型]
```

---

## 伦理挑战

> ⚠️ **高度自主的代理自主决定学习什么** 带来了严峻的伦理问题：

- **目标漂移风险**：代理可能学习与原始目标偏离的能力
- **监督难度**：人类难以追踪代理正在学习什么
- **责任归因**：代理行为后果的责任边界模糊

论文提出这是未来研究必须正视的关键开放问题。

---

## 核心贡献

1. 首次将"主动性"提升到**知识与能力获取**的元层面
2. 提出基于认识论推理的形式化框架
3. 系统梳理长期自主代理中主动学习的伦理挑战

---

## 关键词

`Proactive Learning` · `Long-term Autonomy` · `Epistemic Reasoning` · `Ability Acquisition` · `Agent Ethics` · `AAMAS`
