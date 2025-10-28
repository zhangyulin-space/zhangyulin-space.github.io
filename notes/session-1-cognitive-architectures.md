---
layout: default
title: 'Session 1 — 2024-11-09: Cognitive Architectures for Language Agents — Notes'
---

**Paper**
- Title: Cognitive Architectures for Language Agents
- Authors: Theodore R. Sumers, Shunyu Yao, Karthik Narasimhan, Thomas L. Griffiths
- Year: 2023
- Link: https://arxiv.org/abs/2309.02427

**Overview**
- Explores integrating classic cognitive architecture components (working memory, declarative memory, planning) with LLM agents.
- Argues for structured modules and buffers that support stepwise reasoning and flexible action selection.

**Key Ideas**
- Memory buffers for short-term context; long-term stores for episodic/semantic.
- Planning via decomposition and tool-use; reasoning/action loops.
- Interfaces between symbolic modules and probabilistic LLMs.

**Methods / Evidence**
- Survey and design proposals grounded in agent frameworks; links to ReAct, Reflexion, Toolformer.

**Limitations**
- Empirical validation across tasks is limited; module interfaces may introduce complexity.

**Discussion Questions**
- Which memory abstractions are most effective for long-horizon tasks?
- How to balance modularity with end-to-end learning?
- What signals encourage faithful internal reasoning vs. surface heuristics?
- How should tools be represented to minimize hallucination?
- Where does planning occur: inside LLM vs. external planner?

**Further Reading**
- ReAct (Yao et al., 2022): https://arxiv.org/abs/2210.03629
- Reflexion (Shinn et al., 2023): https://arxiv.org/abs/2303.11366
- Toolformer (Schick et al., 2023): https://arxiv.org/abs/2302.04761