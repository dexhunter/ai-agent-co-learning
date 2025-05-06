# Intensive Co-Learning on AI Agent / AI Agent 残酷共学 <img alt="logo" height="80px" width="80px" src="https://avatars.githubusercontent.com/u/167147327?s=200&v=4" />

## 介绍

本轮残酷共学聚焦 **「AI Agent」** —— 由大型语言模型（LLM）驱动、能自主规划、调用工具并完成任务的新一代智能体。
我们将以顶尖课程 *CS598 Topics in LLM Agents*（UIUC）中涵盖的前沿研究论文为主要学习材料，结合最新研究进展，在三周高强度的论文研读、总结与讨论中，一起深入理解 Agent 的核心概念、关键能力、主流框架及未来挑战。本次共学将特别强调**论文的精读、理解与个人观察的总结**。

### 共学目标

- **深入理解**：系统性学习并掌握 LLM Agent 在推理、记忆、规划、工具调用、多模态处理等关键模块的核心论文和主流方法。
- **总结观察**：针对每周研读的论文，独立完成思考，总结个人观察、批判性见解和潜在的启发。
- **批判与展望**：基于论文学习，评估当前 Agent 技术的局限性（如数据、对齐、安全、人机协作等），并对下一代 Agent / AGI 的发展方向形成自己的思考与展望。

## 关键词

AI Agent，LLM，Tool Use，Planning，Reasoning，Memory，Self-Reflection，Paper Reading

## 面向人群

- 想系统性学习或快速深入理解 Agent 相关前沿研究的 Web3 / AI 开发者、产品经理、研究者
- 有志于将 LLM Agent 的理论知识应用于实际业务流程、DAO 治理或创意生产的实践者
- 喜欢高密度论文阅读、深度思考、总结提炼与热烈讨论的共学型选手

## 报名时间

- 开始时间：2025-06-01
- 结束时间：2025-06-08

## 共学时间

- 开始时间：2025-06-09
- 结束时间：2025-06-29

## 发起人

- 姓名：Dex
- GitHub ID：[dexhunter](https://github.com/dexhunter)
- Telegram：[dexhunt3r](https://t.me/dexhunt3r)
- Email：[i@dex.moe](mailto:i@dex.moe)

## 发起组织

  [LXDAO](lxdao.io) <img alt="organization-logo" height="60px" width="60px" src="https://web3logo.info/detail/LXDAO/1" />

## 请假规则

每周请假 2 次

## 社群
Telegram：<https://t.me/LXDAO/3333>

---

## 学习资料 / 课程安排

> **提示**：核心阅读量较大，请务必提前预习。鼓励深入研读指定论文，并积极总结个人观察与思考。

### Week 1: AI Agent 基础、核心能力（推理、规划与记忆）

**核心议题：** 理解 AI Agent 的基本概念、发展现状以及构成 Agent 智能的关键能力。

**必读论文：**

1.  **Overview & Foundations:**
    * [Language Agents: Foundations, Prospects, and Risks (Slides)](https://language-agent-tutorial.github.io/slides/I-Introduction.pdf) (了解LLM Agent的基本构成、潜力与风险)
    * Section 1-3 of [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U) (对AGI的探讨及LLM Agent在其中的定位)
2.  **Reasoning (推理):**
    * [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) (经典范式：结合推理与行动)
    * [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601) (通过思维树进行更复杂的推理)
3.  **Planning (规划):**
    * [LLM+P: Empowering Large Language Models with Optimal Planning Proficiency](https://arxiv.org/abs/2304.11477) (LLM与规划器结合)
    * [Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models](https://arxiv.org/abs/2310.04406) (LATS框架)
4.  **Memory (记忆):**
    * [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427) (认知架构视角下的Agent记忆)
    * [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831) (受神经生物学启发的长时记忆)

**选读/辅助理解：**
* [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
* [TravelPlanner: A Benchmark for Real-World Planning with Language Agents](https://arxiv.org/abs/2402.01622)

### Week 2: Agent 能力拓展（多模态）、框架（工具使用、RAG、多智能体）与评估

**核心议题：** 探索 Agent 在多模态理解方面的能力，学习构建和增强 Agent 的关键框架，并了解如何评估 Agent 的性能。

**必读论文：**

1.  **Multimodal Understanding (多模态理解):**
    * [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209) (多模态LLM的视觉短板)
    * [VisualWebArena: Evaluating Multimodal Agents on Realistic Visually Grounded Web Tasks](https://arxiv.org/html/2401.13649v2) (多模态Agent在真实网络任务上的评估)
2.  **Tool Use (工具使用):**
    * [ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://arxiv.org/abs/2307.16789) (让LLM掌握大量真实API)
    * [Gorilla: Large Language Model Connected with Massive APIs](https://openreview.net/forum?id=tBRNC6YemY) (LLM与大规模API的连接)
3.  **Retrieval-Augmented Generation (RAG - 检索增强生成):**
    * [Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity](https://arxiv.org/abs/2403.14403) (自适应RAG)
    * [Corrective Retrieval-Augmented Generation](https://arxiv.org/pdf/2401.15884) (纠正性RAG)
4.  **Multi-Agent Systems (多智能体系统):**
    * [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework](https://huggingface.co/papers/2308.08155) (通过多智能体对话构建应用)
    * [CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society](https://arxiv.org/abs/2303.17760) (探索LLM社会性的交互式智能体)
5.  **Agent Evaluation (Agent评估):**
    * [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474) (数字Agent的自主评估与改进)
    * [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132) (基于人类偏好的LLM评估平台)

**选读/辅助理解：**
* [Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection](https://arxiv.org/pdf/2310.11511)
* [What Are Tools Anyway? A Survey from the Language Model Perspective](https://arxiv.org/pdf/2403.15452)
* [Improving Factuality and Reasoning in Language Models through Multiagent Debate](https://arxiv.org/abs/2305.14325)

### Week 3: Agent 应用、挑战与未来展望

**核心议题：** 了解 AI Agent 在不同领域的具体应用，深入探讨其面临的关键挑战（如数据、安全、对齐），并展望其向 AGI 发展的路径。

**必读论文：**

1.  **Agent Application (Agent应用):**
    * **Auto-research:** [ResearchTown: Simulator of Human Research Community](https://github.com/ulab-uiuc/research-town) (模拟人类研究社区)
    * **Coding Agents:** [If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents](https://arxiv.org/abs/2401.00812) (代码如何赋能LLM作为智能体)
    * **Social Agents:** [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) (可交互的人类行为模拟)
    * **Gaming Agents:** [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://voyager.minedojo.org) (开放式具身智能体)
2.  **Challenges from Agents to AGI (从Agent到AGI的挑战):**
    * **Data:** [BAGEL: Bootstrapping Agents by Guiding Exploration with Language](https://arxiv.org/abs/2403.08140) (通过语言引导探索来引导Agent)
    * **Safety:**
        * [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043) (对对齐语言模型的通用和可迁移对抗攻击)
        * [DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698) (GPT模型可信度的综合评估)
    * **Alignment:**
        * [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155) (RLHF经典论文)
        * [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/pdf/2305.18290) (DPO)
3.  **Future Perspectives & Broader Impact:**
    * Section 4-7 of [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U) (再次回顾AGI的讨论，结合已学内容进行思考)

**选读/辅助理解：**
* [The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://arxiv.org/html/2407.19354v1)
* [Position: A Roadmap to Pluralistic Alignment](https://arxiv.org/pdf/2402.05070)
* [Why Johnny Can’t Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompts](https://dl.acm.org/doi/10.1145/3544548.3581388) (关于人机交互与Prompt工程的思考)

### 拓展资源

- UIUC *CS598 Topics in LLM Agents* 完整 [Slides & Paper List](https://github.com/ulab-uiuc/CS598-Topics-in-LLM-Agents)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) (包含Agent相关代码示例)
- [LangGraph 官方教程](https://langchain-ai.github.io/langgraph/tutorials/introduction/) (学习Agentic应用的构建)

---

让我们一起在三周里「快速变态成长」，把纸面知识内化为深刻洞见，共同探索 **AI Agent** 的无限可能 🚀