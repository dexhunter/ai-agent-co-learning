# Intensive Co-Learning on AI Agent / AI Agent 残酷共学 <img alt="logo" height="80px" width="80px" src="https://avatars.githubusercontent.com/u/167147327?s=200&v=4" />

## 介绍  

本轮残酷共学聚焦 **「AI Agent」** —— 由大型语言模型（LLM）驱动、能自主规划、调用工具并完成任务的新一代智能体。  
我们将以 *CS598 Topics in LLM Agents*（UIUC）课程为蓝本，结合最新研究与实作范例，在三周高强度的学习与讨论中，一起拆解 Agent 的核心能力，动手搭建原型，并思考它对未来组织与工作的影响。  

### 共学目标

- **掌握框架**：了解 LLM Agent 在推理、记忆、规划、工具调用、多模态等关键模块的主流方法。  
- **上手实作**：使用开源框架（OpenAI Function Calling、LangGraph、tiny-scientist 等）快速迭代可运行的 Agent demo。  
- **批判与展望**：评估当前技术局限（数据、对齐、安全、人机协作）并提出你对下一代 Agent / AGI 的想象。

## 关键词

AI Agent，LLM，Tool Use，Planning，Self-Reflection

## 面向人群

- 想系统性了解或快速补全 Agent 技术栈的 Web3 / AI 开发者、产品经理、研究者  
- 有志于把 LLM 引入业务流程、DAO 治理或创意生产的实践者  
- 喜欢高密度阅读、讨论与输出的共学型选手  

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

> **提示**：核心阅读量较大，建议提前预习。所有论文均提供中文导读或讨论笔记。  

### Week 1 - AI Agent Overview

- Reading List
1. [How far are we from AGI?](https://openreview.net/pdf?id=H2ZKqfNd0U)

### Week 2 - Agent Ability

- Reading List (Reasoning)
  1. [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)
  2. [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
- Reading List (Memory)
  1. [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831)
  2. [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427)
- Reading List (Planning)
  1. [LLM+P: Empowering Large Language Models with Optimal Planning Proficiency](https://arxiv.org/abs/2304.11477)
  2. [Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models](https://arxiv.org/abs/2310.04406)
- Reading List (Multi-modal Understanding)
  1. [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209)
  2. [VisualWebArena: Evaluating Multimodal Agents on Realistic Visually Grounded Web Tasks](https://arxiv.org/html/2401.13649v2)

### Week 3 - 

- Reading List (Agent Evaluation)
  1. [Autonomous Evaluation and Refinement of Digital Agents](https://arxiv.org/abs/2404.06474)
  2. [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132)
- Reading List (Agent Framework - Tool Use)
  1. [ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://arxiv.org/abs/2307.16789)
  2. [Gorilla: Large Language Model Connected with Massive APIs](https://openreview.net/forum?id=tBRNC6YemY)
- Reading List (Agent Framework - RAG)
  1. [Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity](https://arxiv.org/abs/2403.14403)
  2. [Corrective Retrieval-Augmented Generation](https://arxiv.org/pdf/2401.15884)
- Reading List (Agent Framework - Multi-Agent Systems)
  1. [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework](https://huggingface.co/papers/2308.08155)
  2. [CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society](https://arxiv.org/abs/2303.17760)
- Reading List (Agent Application - Auto-research)
  1. [ResearchTown: Simulator of Human Research Community](https://github.com/ulab-uiuc/research-town)
  2. [Can Large Language Models Provide Useful Feedback on Research Papers? A Large-scale Empirical Analysis](https://arxiv.org/pdf/2310.01783)
- Reading List (Agent Application - Coding Agents)
  1. [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741)
  2. [If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents](https://arxiv.org/abs/2401.00812)
- Reading List (Agent Application - Social Agents)
  1. [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442)
  2. [SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents](https://arxiv.org/abs/2310.11667)
- Reading List (Agent Application - Gaming Agents)
  1. [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://voyager.minedojo.org)
  2. [MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge](https://arxiv.org/abs/2206.08853)
- Reading List (Challenges - Data)
  1. [BAGEL: Bootstrapping Agents by Guiding Exploration with Language](https://arxiv.org/abs/2403.08140)
  2. [SOAR: Autonomous Improvement of Instruction Following Skills via Foundation Models](https://auto-improvement.github.io/)
- Reading List (Challenges - Safety)
  1. [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)
  2. [DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698)
- Reading List (Challenges - Alignment)
  1. [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155)
  2. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/pdf/2305.18290)

### 拓展资源

- UIUC *CS598 Topics in LLM Agents* 完整 [Slides & Paper List](https://github.com/ulab-uiuc/CS598-Topics-in-LLM-Agents)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
- [LangGraph 官方教程](https://langchain-ai.github.io/langgraph/tutorials/introduction/)

---

让我们一起在三周里「快速变态成长」，把纸面知识变成真正跑得起来的 **AI Agent** 🚀
