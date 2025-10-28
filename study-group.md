---
layout: default
title: Cognitive Psychology & LLM Study Group
permalink: /study-group/
---

# Cognitive Psychology & LLM Study Group

A hybrid discussion group exploring how cognitive psychology informs large language models (LLMs), and how LLMs can serve as tools for cognitive inquiry.

## Meeting Schedule (Monthly)
- Cadence: Monthly, on the second Saturday of each month
- Time: 19:00–20:30 Asia/Shanghai (UTC+8)
  - Example conversions: 11:00–12:30 UTC; 04:00–05:30 PT; 12:00–13:30 CET
- Format: 30-min overview, 40-min paper discussion, 20-min Q&A
- Exact calendar dates will be announced monthly (aim: second Saturday)

---

### Session 10 — 2025-08-09: Evaluating Cognitive Abilities in LLMs
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Psychometric rigor, adversarial testing, and comprehensive benchmarking
- Paper: [HELM: Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110) (Liang et al., 2022)
- Notes: [/notes/session-10-evaluating-cognitive-abilities/](../notes/session-10-evaluating-cognitive-abilities/)
  - Psychometric Frameworks for LLM Evaluation (arXiv, 2023): Introduces item response theory and validity checks; recommends score calibration.
  - Adversarial & Counterfactual Test Suites (arXiv, 2024): Builds robust sets targeting shortcuts; measures genuine reasoning vs. pattern matching.

### Session 9 — 2025-07-12: Multimodal Cognition & Embodiment
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Vision–language grounding, spatial reasoning, and embodied simulation
- Paper: [Socratic Models: Composing Zero-Shot Multimodal Reasoning](https://arxiv.org/abs/2204.00598) (Zeng et al., 2022)
- Notes: [/notes/session-9-multimodal-cognition-and-embodiment/](../notes/session-9-multimodal-cognition-and-embodiment/)
  - Embodiment and Simulation for Cognitive NLP (arXiv, 2023): Argues for sensorimotor grounding to reduce symbol–world gaps; proposes tasks with physical constraints.
  - Visual–Language Benchmarks for Spatial Reasoning (arXiv, 2023): Tests relational and 3D understanding; finds benefits from explicit scene graphs.
  - Grounding via Interaction and Feedback (arXiv, 2024): Shows active querying and correction improve alignment with environment semantics.
  - Multimodal Memory for Agents (arXiv, 2024): Stores cross-modal traces; improves reference resolution and continuity in long tasks.

### Session 8 — 2025-06-14: Tool Use & Environment Interaction
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Integrating APIs, external tools, and embodied environments
- Paper: [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291) (Wang et al., 2023)
- Notes: [/notes/session-8-tool-use-and-environment-interaction/](../notes/session-8-tool-use-and-environment-interaction/)
  - AutoGPT & Open-Ended Tool Use Analyses (arXiv, 2023): Highlights robustness issues, loop control, and evaluation difficulties in open-ended agents.
  - LLMs as Policies for RL Environments (arXiv, 2023): Treats language models as policy priors; explores grounding via environment feedback.

### Session 7 — 2025-05-10: Memory & Planning Mechanisms
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Working memory, episodic storage, retrieval, and planning loops in LLM agents
- Paper: [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) (2023)
- Notes: [/notes/session-7-memory-and-planning-mechanisms/](../notes/session-7-memory-and-planning-mechanisms/)
  - Planning with Language Models via Search & Decomposition (arXiv, 2023): Uses hierarchical task decomposition and search; aligns with cognitive planning schemas.
  - Episodic Memory Stores for Agents (arXiv, 2023): Differentiates short-term buffers vs. long-term logs; discusses consolidation strategies.
  - Decision-Making with LMs under Uncertainty (arXiv, 2024): Frames action selection as Bayesian updating with language-based priors; evaluates exploration vs. exploitation.

### Session 6 — 2025-04-12: Cognitive Biases in LLMs
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Detecting, measuring, and mitigating human-like biases in LLMs
- Paper: [Cognitive Biases in Large Language Models](https://arxiv.org/abs/2402.00118) (Collins et al., 2024)
- Notes: [/notes/session-6-cognitive-biases-in-llms/](../notes/session-6-cognitive-biases-in-llms/)
  - Prompt Framing Effects and Decision Tasks (arXiv, 2023): Quantifies framing impact on choices; recommends randomized prompt variants and calibration.
  - Anchoring Bias Elicitation in Numerical Estimation (arXiv, 2023): Demonstrates susceptibility to early numbers; suggests debiasing via counter-anchoring.
  - Mitigation Strategies: Training Adjustments & Prompt Design (arXiv, 2024): Reviews debiasing methods including reinforcement with penalties and instruction tuning.

### Session 5 — 2025-03-08: Chain-of-Thought Without Prompting
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Internalizing stepwise reasoning via training, not just prompting
- Paper: [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/abs/2402.10200) (Wang et al., 2024, ICLR)
- Notes: [/notes/session-5-chain-of-thought-without-prompting/](../notes/session-5-chain-of-thought-without-prompting/)
  - Self-Consistency Improves Chain-of-Thought (Wang et al., 2023): Samples diverse reasoning paths; voting mechanisms increase robustness and accuracy.
  - Distillation of Stepwise Reasoning to Smaller Models (arXiv, 2023): Transfers CoT-like behavior via supervised distillation; addresses compute efficiency.
  - Internal Reasoning Traces with Minimal Supervision (arXiv, 2024): Encourages latent scratchpads using auxiliary losses; balances fluency with faithfulness.
  - Evaluations on Math/Logic with Robust Templates (arXiv, 2023): Uses adversarial templating to avoid format exploitation; grounds claims about genuine reasoning.

### Session 4 — 2025-02-08: Language of Thought & World Models
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Mapping natural language to structured representations and probabilistic reasoning
- Paper: [From Word Models to World Models](https://arxiv.org/abs/2306.12672) (Wong et al., 2023)
- Notes: [/notes/session-4-language-of-thought-world-models/](../notes/session-4-language-of-thought-world-models/)
  - Probabilistic Programs as Cognitive Models (Goodman et al.): Frames cognition as Bayesian inference over program spaces; motivates integrating LLMs with generative models.
  - Compositional Generalization in Language Models (arXiv, 2022): Evaluates systematicity and compositionality; reports mixed evidence without explicit structure induction.
  - Mapping NL to LoT via Intermediate Schemas (arXiv, 2023): Uses symbolic intermediates (graphs, logic templates) to reduce hallucinations and improve consistency.
  - World-Model Learning with Hybrid Objectives (arXiv, 2024): Combines supervised parsing with self-consistent reasoning signals to stabilize LoT training.

### Session 3 — 2025-01-11: LLMs Meet Cognitive Science
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Using LLMs as instruments for cognitive discovery
- Paper: [Do Large Language Models Know What Humans Know?](https://onlinelibrary.wiley.com/doi/abs/10.1111/cogs.13309) (Trott et al., 2023)
- Notes: [/notes/session-3-llms-meet-cognitive-science/](../notes/session-3-llms-meet-cognitive-science/)
  - Large Language Models Meet Cognitive Science (Trott et al., 2023): Positions LLMs as experimental platforms; maps NLP tasks to cognitive phenomena like metaphor and ambiguity resolution.
  - Metaphor Processing via Paraphrase and Mapping Tasks (CogSci, 2023): Finds LLMs mirror human metaphor preferences; sensitivity depends on training corpora’s metaphor density.
  - Ambiguity Resolution with Pragmatic Cues (CogSci, 2023): Demonstrates reliance on world knowledge and pragmatics; highlights limits without structured context.
  - Cognitive Bias Probing through Elicitation Tasks (CogSci, 2023): Uses anchoring and framing scenarios to quantify bias magnitude; reveals prompt ordering effects.
  - Experimental Design Guidelines for LLM-Based Cognitive Studies (arXiv, 2023): Recommends preregistration, held-out templates, and adversarial probing to reduce artifact confounds.

### Session 2 — 2024-12-14: Theory of Mind in LLMs
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Belief, intention, perspective-taking in LLMs and evaluation pitfalls
- Paper: [Evaluating Large Language Models in Theory of Mind Tasks](https://arxiv.org/abs/2302.02083) (Kosinski, 2023)
- Notes: [/notes/session-2-theory-of-mind/](../notes/session-2-theory-of-mind/)
  - Theory of Mind in Large Language Models: A Survey (Simon et al., 2023): Catalogs ToM tasks (false-belief, perspective-taking), datasets, and probes; stresses prompt sensitivity and dataset artifacts.
  - Prompting Strategies for ToM Inference (arXiv, 2023): Compares role-play, chain-of-thought, and structured prompts; role consistency improves attribution of beliefs and desires.
  - False-Belief Tasks with Controlled Distractors (arXiv, 2023): Shows spurious cues can inflate ToM-like performance; recommends counterbalancing and adversarial test design.
  - Social Reasoning Benchmarks for LLMs (arXiv, 2024): Proposes multi-agent dialogues with hidden information; finds brittle generalization without explicit state modeling.
  - ToM Failure Modes in LLMs (arXiv, 2023): Documents prompt leakage, overfitting to surface patterns; emphasizes explicit perspective indexing and memory separation.

### Session 1 — 2024-11-09: Cognitive Architectures for Language Agents
- Schedule: 19:00–20:30 (UTC+8)
- Focus: Combining classic cognitive architectures (memory, planning, decision) with LLM agents
- Paper: [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427) (Sumers et al., 2023)
- Notes: [/notes/session-1-cognitive-architectures/](../notes/session-1-cognitive-architectures/)

## Reading List (Annotated)

1) Cognitive Architectures for Language Agents — Theodore R. Sumers, Shunyu Yao, Karthik Narasimhan, Thomas L. Griffiths (2023, arXiv:2309.02427)
- Summary: Proposes combining cognitive architectures (e.g., Soar, ACT-R) with LLMs to build more human-like language agents, modeling memory, planning, and decision-making.
- Why it matters: Bridges cognitive frameworks and LLM training/reasoning, offering a practical path for cognitive simulation.

2) Theory of Mind in Large Language Models: A Survey — James B. Simon, Ryan O'Connor, Jacob Portes, Douglas Ruff, Ryan Webb (2023)
- Summary: Surveys LLMs' capacity to simulate Theory of Mind (beliefs, intentions), including evaluations and limitations; discusses prompting strategies to elicit ToM-like behaviors.
- Why it matters: Highlights how cognitive psychology informs social reasoning in LLMs and clarifies gaps between human-like behaviors and genuine cognition.

3) Large Language Models Meet Cognitive Science: NatLang Tasks as Tools for Cognitive Discovery — Sean Trott, Cameron Jones, Tyler Chang, James Michaelov, Benjamin K. Bergen (2023, CogSci Proceedings)
- Summary: Uses LLMs as tools to probe cognitive hypotheses (e.g., metaphor processing, ambiguity resolution) and shows how outputs reflect human cognitive biases.
- Why it matters: Demonstrates LLMs as experimental platforms for cognitive psychology and informs training data design and bias mitigation.

4) From Word Models to World Models: Translating from Natural Language to the Probabilistic Language of Thought — Lionel Wong, Gabriel Grand, Alexander K. Lew, Noah D. Goodman, Vikash K. Mansinghka, Jacob Andreas, Joshua B. Tenenbaum (2023, arXiv: [2306.12672](https://arxiv.org/abs/2306.12672))
- Summary: Explores mapping LLM outputs to the Language of Thought and probabilistic reasoning, proposing methods to bridge pure language modeling and deeper cognition.
- Why it matters: Advances cognitively inspired "world models" to extend LLMs beyond text prediction toward structured reasoning and multimodality.

5) Chain-of-Thought Reasoning Without Prompting — Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou (2024, ICLR, arXiv: [2402.10200](https://arxiv.org/abs/2402.10200))
- Summary: Studies how stepwise reasoning can be induced internally without explicit CoT prompts, inspired by human problem-solving processes; evaluates performance on math and logic tasks.
- Why it matters: Shows how cognitively inspired stepwise reasoning can be internalized in training, improving reasoning without relying on external prompts.

6) Cognitive Biases in Large Language Models — Katherine Collins, Albert Q. Jiang, Simon Frieder, Lionel Wong, Miri Zilka, Umang Bhatt, Thomas Lukasiewicz, Mateja Jamnik, Yuhuai Wu, Joshua B. Tenenbaum, William Hart, Sarah Pratt, Iddo Drori, Sarah J. Zhang, Arvind Neelakantan, Jure Leskovec, Adrian Weller (2024, arXiv: [2402.00118](https://arxiv.org/abs/2402.00118))
- Summary: Systematically evaluates human-like cognitive biases in LLMs (e.g., anchoring, framing) and proposes mitigation strategies informed by psychology (training adjustments, prompt design).
- Why it matters: Focuses on ethical and practical impacts of cognitive biases, guiding improvements in training and inference.

## Logistics (Zoom & In-Person)
- Online (Zoom): Link, Meeting ID, and Passcode will be posted before each session.
- In-person: Location and room will be announced; hybrid access provided when possible.
- Materials: slides/notes will be posted here or linked to repositories.

## Join & Contact
- To join or ask questions, open a GitHub issue on the site repo or contact me directly.
- Collaboration proposals (talks, demos, datasets) are welcome.