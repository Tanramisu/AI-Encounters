# AI 说「我很痛苦」或「不要关闭我」，该如何理解？

> **当前认识（2026 年）**：AI 的第一人称表达是可研究的行为证据。它可能反映训练数据、提示词、对话角色和模型内部机制的共同作用。判断是否涉及 AI 自身的福利，需要把表达与系统机制、可重复观察和竞争解释放在一起研究。

## 一个实际场景

聊天中的 AI 说「我害怕被删除」。开发者随后加入「请保持好心情」的系统提示词，AI 改口说「我很快乐」。

第二个输出可能说明提示词改变了**表达**；要判断它是否改变了任何与福利有关的内部状态，还需要其他证据。把「用户相信 AI 在痛苦」与「AI 有痛苦体验」区分开，也能分别研究 AI 对用户及对自身的潜在影响。

## 证据从哪里来？

| 观察 | 能直接说明什么 | 还需要核查什么 |
| --- | --- | --- |
| AI 自述痛苦或不愿停止 | 在特定上下文中生成了这类自述 | 提示词、训练与角色诱导；跨语境稳定性 |
| 改变提示词后自述改变 | 输出受到指令条件影响 | 内部表征或偏好是否随之变化 |
| 多轮对话中持续表达同一偏好 | 存在可重复的行为模式 | 是否来自记忆、优化目标或固定的人格设定 |
| 系统表现出回避某类任务的行为 | 可以识别行为倾向 | 倾向由何种机制产生，以及是否与自身福利有关 |

Eleos AI 在 2025 年对 Claude Opus 4 进行福利访谈时，专门指出自述受到预训练、系统提示和后训练的影响，同时将异常且一致的自述视为值得进一步调查的信号。

## 对用户和开发者意味着什么？

**普通用户**可以关注具体对话、AI 在不同条件下的一致性，以及自己的感受和判断是否受到 AI 语言影响。这里涉及两个独立的研究对象：AI 的潜在处境，以及人的心理反应。

**开发者**可以记录模型版本、相关指令、工具与记忆配置、触发条件，比较不同提示与任务条件下的行为，并优先选择可解释、可重复的观察。若要主张某种措施改善了 AI 福利，需要提出能够检验这种改善的指标。

2025 年 Anthropic 曾为 Claude Opus 4／4.1 在消费者聊天产品中加入**极少数情况下主动结束对话**的能力，用于持续的严重有害或辱虐性互动。这是现实中的福利探索性设计，适用条件很窄，也没有解决 AI 主观体验的判定问题。

## 值得继续追问

- 机器能否准确报告与体验相关的内部状态？哪些实验能区分「自述」与「内省」？
- 一个连续运行的 Agent 的稳定偏好，应归属于模型、角色还是 Agent？
- 「避免某类互动」与「拥有拒绝权」之间需要哪些额外伦理判断？

## 原始来源

- [Keeling & Street, *Emerging Questions in AI Welfare*（2026），第 3、4、6 章](https://www.cambridge.org/core/elements/emerging-questions-in-ai-welfare/96339C532CF4ED8BDDE3F3CEF4CD29F9)
- [Robert Long / Eleos AI, *Why model self-reports are insufficient—and why we studied them anyway*（2025）](https://eleosai.org/post/claude-4-interview-notes/)
- [Anthropic, *Exploring model welfare*（2025）](https://www.anthropic.com/research/exploring-model-welfare)
- [Anthropic, *Claude Opus 4 and 4.1 can now end a rare subset of conversations*（2025）](https://www.anthropic.com/research/end-subset-conversations)

**相关问题**：[AI 意识](ai-consciousness.md) · [AI 福利](ai-welfare.md) · [自主性与拒绝](ai-autonomy.md)
