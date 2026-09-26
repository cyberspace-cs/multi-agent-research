# 📄 Multi-Agent 动态角色与博弈机制 论文索引

> 按方向分类，附核心观点和笔记

---

## 📚 综述类

| # | 论文 | 链接 | 核心观点 |
|---|------|------|----------|
| 1 | Game-Theoretic Lens on LLM-based Multi-Agent Systems | [arXiv](https://arxiv.org/html/2601.15047v1) | 用博弈论四要素统一分析 LLM MAS |
| 2 | LLM-Based Multi-Agent Orchestration Survey | [Preprints](https://www.preprints.org/manuscript/202604.2147) | 三种任务分配策略 + 优化分配 |
| 3 | LLM-Based Autonomous Multi-Agent Systems Survey | [PDF](https://nanoagentteam.github.io/assets/autonomous-multi-agent-survey.pdf) | 功能专业化 vs 领域专业化 |
| 4 | Reinforcement Learning for LLM MAS | [arXiv](https://arxiv.org/html/2605.02801) | RL 训练多 Agent 系统，附 84 篇论文合集 |

---

## 🎭 方向 1：动态角色分配

| # | 论文 | 链接 | 核心观点 | 笔记 |
|---|------|------|----------|------|
| 1 | Meta-Debate | [arXiv](https://arxiv.org/html/2601.17152) | 辩论前先跑元辩论，根据能力选角色 | ⭐ 必读 |
| 2 | MetaGen: Self-Evolving Roles and Topologies | [arXiv](https://arxiv.org/html/2601.19290) | 角色和拓扑都可以自我演化 | |
| 3 | MADC: Key Decision-Makers in Multi-Agent Debates | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/download/40235/44196) | "Truth Last"策略：知道答案的放最后，提升 22% | ⭐ 反直觉发现 |
| 4 | R3DM: Role Discovery through Dynamics Models | [arXiv](https://arxiv.org/html/2505.24265) | 最大化角色和轨迹的互信息 | |

---

## 💬 方向 2：多 Agent 辩论与博弈

| # | 论文 | 链接 | 核心观点 | 笔记 |
|---|------|------|----------|------|
| 1 | PEAR: Permutation-Equivariant Adaptive Routing | [GitHub](https://github.com/EVIEHub/PEAR) | 动态重构通信拓扑，"角色稳定性"是隐性瓶颈 | ⭐ 已 fork |
| 2 | DynaDebate: Dynamic Path Generation | [arXiv](https://arxiv.org/html/2601.05746) | 每个 Agent 走不同推理路径 | |
| 3 | Bilevel Coordinated Reflection | [arXiv](https://arxiv.org/html/2609.02750v1) | 双层协调博弈，orchestrator-worker 是势博弈 | |
| 4 | MoD: Mixture of Debaters | [GitHub](https://github.com/YongLD/MoD) | 单模型内用 MoE 做自我辩论，token 少 87% | ⭐ 效率革命 |
| 5 | Courtroom-Style Multi-Agent Debate | [GitHub](https://github.com/mnc13/PROClaim) | 法庭式：原告 + 被告 + 3 个法官 | |

---

## 🕸️ 方向 3：通信拓扑与稀疏连接

| # | 论文 | 链接 | 核心观点 |
|---|------|------|----------|
| 1 | PEAR | [GitHub](https://github.com/EVIEHub/PEAR) | 动态稀疏拓扑 |
| 2 | Belief-Driven Multi-Agent Collaboration | [arXiv](https://arxiv.org/html/2603.24973v1) | 近似完美贝叶斯均衡 |

---

## 🤝 方向 4：激励机制与合作博弈

| # | 论文 | 链接 | 核心观点 |
|---|------|------|----------|
| 1 | MAC-SPGG: Sequential Public Goods Games | [AAMAS](https://www.ifaamas.org/Proceedings/aamas2026/pdfs/SJPO2377.pdf) | 让努力贡献成为子博弈完美纳什均衡 |
| 2 | DRIVE: Dynamic Reward Incentives | [arXiv](https://arxiv.org/html/2601.06382v1) | 动态奖励应对不断变化的收益 |
| 3 | Lyapunov-guided Cooperative Games | - | 合作微分博弈，约束融合 |
| 4 | Strategic Persuasion in Legal Argumentation | [arXiv](https://arxiv.org/html/2604.07028v1) | 特质条件化的法律辩论 |

---

## 🎭 方向 5：身份与人格的博弈效应

| # | 论文 | 链接 | 核心观点 | 笔记 |
|---|------|------|----------|------|
| 1 | When Identity Overrides Incentives | [arXiv](https://arxiv.org/html/2601.10102v5) | 人格设定压制收益对齐行为，99% 偏向某一方 | ⭐ 反直觉！ |
| 2 | LinguaGame | - | 语言学 grounded 的信号博弈 | |
| 3 | Werewolf Arena | [GitHub](https://github.com/google/werewolf_arena) | Google 出品，用狼人杀评测 LLM |

---

## 🧠 方向 6：多 Agent 强化学习

| # | 论文 | 链接 | 核心观点 |
|---|------|------|----------|
| 1 | Stronger-MAS | [arXiv](https://arxiv.org/html/2510.11062) | 角色专业化策略，每个 Agent 独立更新 |
| 2 | Dynamic Strategy Adaptation | [arXiv](https://arxiv.org/html/2507.02002v3/) | LLM 符号评估 + RL，实时适应策略 |

---

## 📦 开源项目清单

### 研究型
| 项目 | 地址 | 状态 |
|------|------|------|
| PEAR | https://github.com/EVIEHub/PEAR | ✅ 已 fork |
| MoD | https://github.com/YongLD/MoD | ⏳ 待 fork |
| PROClaim | https://github.com/mnc13/PROClaim | ⏳ 待 fork |
| MADC | https://github.com/SG-XM/AAAI2026-MADC | ⏳ 待 fork |
| Werewolf Arena | https://github.com/google/werewolf_arena | Google 出品 |
| awesome-llm-mas-rl | https://github.com/xxzcc/awesome-llm-mas-rl | 84 篇论文 |

### 工业级框架
| 框架 | 地址 | 特点 |
|------|------|------|
| CrewAI | https://github.com/crewAIInc/crewAI | 角色团队，最快上手 |
| LangGraph | https://github.com/langchain-ai/langgraph | 有状态工作流 |
| AutoGen | https://github.com/microsoft/autogen | 微软研究风格 |
| AGNO | https://github.com/agno-agi/agno | 轻量生产级 |
| Camel | https://github.com/camel-ai/camel | 角色扮演对话 |

---

## 💡 关键发现笔记

### 1. 博弈论什么时候有用？
- ✅ **收益对齐时**：减少 79% 幻觉
- ❌ **各怀鬼胎时**：合作崩溃，需要正式调解

### 2. 人格设定的陷阱
- 给 Agent 设定人格，反而破坏博弈均衡
- 人格会让 Agent 偏向某一方，不管收益怎么设
- 要恢复理性，必须去掉人格 + 明确收益

### 3. "Truth Last" 为什么有效？
- 知道答案的人放最后发言
- 前面的人先自由讨论，最后一个人再定调
- 性能提升高达 22%

### 4. 多 Agent 辩论的坑
- 不对称校准：有的过度自信，有的过度谦虚
- 可能收敛到错误答案，而不是正确答案
- 不是 Agent 越多越好

---

## 🎯 我们的研究方向

**Jev 当博弈裁判：**
1. 角色分配：Jev 判断谁适合什么角色
2. 辩论流程：Jev 判断还要不要继续
3. 最终裁决：Jev 综合判断

**优势：**
- 比大模型快 10 倍
- 便宜 100 倍
- 上下文不爆炸

这是一个没人做过的方向！
