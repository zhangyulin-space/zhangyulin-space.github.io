---
layout: default
title: 'Session 5 — 2025-03-08: Chain-of-Thought Without Prompting — Notes'
---

**Paper**
- Title: Chain-of-Thought Reasoning Without Prompting
- Authors: Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou
- Year: 2024 (ICLR)
- Link: https://arxiv.org/abs/2402.10200

**Overview**
- Demonstrates training signals can induce latent multi-step reasoning without explicit CoT prompts.

**Key Ideas**
- Auxiliary losses and self-consistency for robust reasoning.

**Methods / Evidence**
- Math/logic benchmarks; analysis of internal traces.

**Limitations**
- Balancing fluency with faithful reasoning; risk of brittle traces.

**Discussion Questions**
- What supervision induces reliable internal scratchpads?
- How to evaluate latent reasoning beyond formatted outputs?
- Distillation strategies to smaller models.