---
layout: post
title: Geoffrey Hinton Talk Notes 1 — Representations and Learning
date: 2025-07-10
categories: [notes, hinton]
---

# Geoffrey Hinton Talk Notes 1 — Representations and Learning

Video: https://www.youtube.com/watch?v=6fvXWG9Auyg

**Core Ideas**
- Distributed representations encode concepts as high-dimensional activation patterns, not discrete symbols.
- Error-driven learning (e.g., backprop or forward-forward variants) iteratively refines layered representations.
- Scaling and better architectures tend to produce emergent capabilities and nonlinear gains.
- Generative modeling reframes “understanding” as the ability to predict, reconstruct, and imagine.

**Cognitive Psychology Connections**
- Categorization: prototypes and family resemblance align with distributed, graded representations.
- Perception: hierarchical features support bottom-up pattern extraction and top-down influence.
- System 1 vs. System 2: fast parallel inference vs. serial reasoning echoes model behaviors.

**Mini Examples**
- Visual features: early layers capture edges/textures; deeper layers capture parts/objects.
- Semantic structure: embeddings cluster related meanings and support analogy-like inferences.

**Study Prompts**
- Build a small CNN and visualize layer-wise features; relate them to perceptual stages.
- Use embeddings to run categorization tasks; compare prototype vs. exemplar predictions.
- Contrast backprop with forward-forward in a toy setting; track convergence and robustness.

**Further Reading**
- Hinton on distributed representations and representation learning.
- Reviews on emergence in large-scale models and generative modeling.