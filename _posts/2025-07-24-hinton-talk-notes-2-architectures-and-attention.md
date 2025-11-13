---
layout: post
title: Geoffrey Hinton Talk Notes 2 — Architectures and Attention
date: 2025-07-24
categories: [notes, hinton]
---

# Geoffrey Hinton Talk Notes 2 — Architectures and Attention

Video: https://www.youtube.com/watch?v=6fvXWG9Auyg

**Core Ideas**
- Attention mechanisms implement differentiable selection, weighting relevant information for conditional computation.
- Transformers scale sequence modeling by parallel attention over tokens, enabling long-range dependencies.
- Generative models unify perception and production: the same system predicts and imagines.
- Architectural bias (depth, width, recurrence) shapes what kinds of patterns are easy to learn.

**Cognitive Psychology Connections**
- Attentional control: selecting task-relevant cues mirrors human top-down attention.
- Working context: self-attention resembles maintaining and updating a flexible, task-specific context.
- Language and thought: sequence modeling illuminates syntactic/semantic integration across time.

**Mini Examples**
- Masked language modeling as anticipatory processing akin to predictive coding.
- Cross-attention for multimodal grounding (text-image alignment) and referential disambiguation.

**Study Prompts**
- Implement toy self-attention; visualize attention maps and relate them to cue selection.
- Compare RNN vs. Transformer on long-range tasks; analyze failure modes and biases.
- Test generative-consistency: probe whether generated hypotheses improve downstream classification.

**Further Reading**
- Attention is All You Need and follow-up works on efficient attention.
- Predictive processing accounts in cognitive science and neuroscience.