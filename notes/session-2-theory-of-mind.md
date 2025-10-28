---
layout: default
title: 'Session 2 — 2024-12-14: Theory of Mind in LLMs — Notes'
---

**Paper**
- Title: Evaluating Large Language Models in Theory of Mind Tasks
- Author: Michal Kosinski
- Year: 2023
- Link: https://arxiv.org/abs/2302.02083

**Overview**
- Assesses ToM-like performance on controlled false-belief and related tasks.
- Compares model generations with human benchmarks, highlighting prompt sensitivity.

**Key Ideas**
- Structured task templates reduce format exploitation.
- Larger models show higher task success; stability depends on prompting.

**Methods / Evidence**
- Battery of story-based tasks with controls and reversals; cross-model comparison.

**Limitations**
- Behavioral success may not reflect robust internal state modeling.
- Dataset artifacts and leakage risk.

**Discussion Questions**
- What constitutes genuine ToM vs. clever text inference?
- How to design adversarial controls that target shortcuts?
- Can role-play or memory separation improve robustness?
- How to measure representational ToM (belief states) beyond QA?
- Safety risks of advanced ToM in deployed systems?

**Further Reading**
- ToMBench (2023)
- FANToM (2023)