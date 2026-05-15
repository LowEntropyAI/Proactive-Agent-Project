# AppAgent-Pro: A Proactive GUI Agent System for Multidomain Information Integration and User Assistance

## 基本信息

| 字段 | 内容 |
|------|------|
| **会议** | CIKM 2025 (ACM International Conference on Information and Knowledge Management) |
| **arXiv ID** | [arXiv:2508.18689](https://arxiv.org/abs/2508.18689) |
| **作者** | LaoKuiZe et al. |
| **代码** | [github.com/LaoKuiZe/AppAgent-Pro](https://github.com/LaoKuiZe/AppAgent-Pro) |
| **领域** | cs.AI |

---

## 一句话总结

首个**主动式** GUI 代理系统：不等用户明确指令，而是主动整合跨域信息，推断用户深层需求并提前介入，从根本上重新定义日常信息获取方式。

---

## 动机

现有 LLM 代理几乎全部工作在**被动（Reactive）范式**下：只响应用户明确输入的指令。这带来两个问题：
- 用户需要花大量时间分解任务并逐步指导代理
- 代理无法主动发现用户潜在的信息需求，导致信息获取不全面

AppAgent-Pro 主张：真正强大的 GUI 代理应该像一位有经验的助理——在用户说话之前，已经预判好下一步。

---

## 方法

AppAgent-Pro 构建了一套主动信息整合闭环：

```
用户指令
    ↓
意图推断模块（从单一指令推断潜在、深层信息需求）
    ↓
跨域信息挖掘（主动在多个应用/数据源间检索）
    ↓
主动辅助生成（综合结果，主动呈现用户未要求但有用的信息）
```

核心机制：
1. **意图前向推断**：基于当前 GUI 上下文和用户历史，推断未来 2-3 步的潜在需求
2. **多域并行检索**：不局限于当前应用，主动跨应用搜集相关信息
3. **主动呈现**：在用户发起下一条指令之前，将整合好的信息推送给用户

---

## 核心结论

- AppAgent-Pro 在信息整合的广度和深度上显著优于被动式 GUI 代理
- 主动预判使用户无需多次追问即可获得更完整的结果
- 系统在多域任务（跨 App、跨平台）中表现尤为突出

---

## 与项目的关联

AppAgent-Pro 是本项目**"GUI/Mobile/OS Proactive Agents"**类别最直接的代表论文之一：
- 操作对象是 GUI（应用界面）
- 核心贡献在于从 Reactive → Proactive 的范式转变
- 多域信息整合与潜在需求预判是本项目关注的核心主题

---

## 关键词

`Proactive Agent` · `GUI Agent` · `Multidomain Information Integration` · `User Intent Anticipation` · `Mobile/Desktop` · `CIKM 2025`
