---
layout: post
title: Geoffrey Hinton Talk Notes 3 — Memory and Continual Learning
date: 2025-08-07
categories: [notes, hinton]
---

# Geoffrey Hinton Talk Notes 3 — Memory and Continual Learning

Video: https://www.youtube.com/watch?v=6fvXWG9Auyg

**Core Ideas**
- Catastrophic forgetting: training on new tasks can overwrite older knowledge without safeguards.
- Consolidation strategies: regularization, replay, and structured memory buffers help preserve past skills.
- Representation stability vs. plasticity: balancing the need to learn new patterns while keeping old.
- Forward-forward perspective: exploring more biologically plausible local learning signals.

**Cognitive Psychology Connections**
- Memory systems: episodic vs. semantic mirrors buffer vs. weight-level knowledge.
- Consolidation: sleep-like replay relates to experience reactivation and integration.
- Interference: proactive/retroactive interference analogizes task overlap in model training.

**Mini Examples**
- Continual learning benchmarks (e.g., split datasets) show forgetting without replay.
- Embedding drift: track how representations shift across sequential tasks.

**Study Prompts**
- Implement a simple replay buffer; measure performance retention across tasks.
- Test regularization methods (EWC/LwF-like ideas) and compare to naive fine-tuning.
- Explore local learning signals; evaluate convergence and data efficiency on small problems.

**Further Reading**
- Surveys on continual learning and memory consolidation in neural networks.
- Biological learning and synaptic consolidation literature.