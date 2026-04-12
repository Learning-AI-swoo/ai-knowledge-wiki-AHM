---
title: Mechanical Interpretability for TCM
status: active
priority: 1
parent: "[[vuim-ai-lab|VUIM AI Lab]]"
last_updated: 2026-04-11
---

# Mechanical Interpretability for TCM

## Overview
Research project applying [[Mechanistic Interpretability]] techniques — activation patching, persona vectors, Sparse Autoencoder (SAE) decomposition — to understand how LLMs process Traditional Chinese Medicine (TCM) domain knowledge. The core question: **can we make the "black box" transparent for Eastern medical reasoning?**

This is the Lab's highest-priority project because it sits at the intersection of two unique strengths: Sung's technical MI research experience (activation patching) and VUIM's TCM domain expertise.

## Research Questions
1. How do LLMs internally represent TCM concepts (qi, meridians, five elements) vs. Western biomedical concepts?
2. Can persona vector techniques reveal TCM-specific "reasoning directions" in activation space?
3. Where do LLMs hallucinate most dangerously in TCM clinical contexts?
4. Can preventative steering suppress TCM-specific hallucination patterns without degrading general medical performance?

## Methodology

### Activation Patching
Isolating which model components (attention heads, MLP layers) are causally responsible for TCM-related outputs. Sung's existing patching work provides the technical foundation.

### Persona Vectors for TCM
Adapted from [[persona-vectors-character-traits]]: extract linear directions in activation space corresponding to TCM reasoning traits (e.g., holistic vs. reductive diagnosis, pattern differentiation vs. differential diagnosis). The [[Anthropic]] research team's automated extraction pipeline (trait description → contrastive prompts → response generation → vector extraction) is directly applicable.

### SAE Decomposition
Using Sparse Autoencoders to decompose TCM-relevant activation patterns into fine-grained interpretable features — analogous to how the persona vectors paper decomposed "evil" into sub-features (profanity, hacking, torture).

## Source Connections

### Direct Methodology Sources
- [[persona-vectors-character-traits]] (#012) — **strongest link**: persona vector extraction and steering; Sung notes "maybe test it with my Patching work"
- [[monitoring-ai-chain-of-thought]] (#007) — CoT monitoring ensures transparent reasoning; paradigm: "design models that must reveal their thinking"
- [[understanding-in-context-learning]] (#001) — ICL mechanism (implicit weight updates) explains how TCM prompts affect model computation

### Medical AI Context
- [[future-ai-healthcare-conflicts]] (#010) — the "black box" barrier is what MI research aims to solve
- [[adversarial-hallucinations-medical-ai]] (#029) — 65.9% hallucination rate on adversarial clinical vignettes; understanding WHY models hallucinate requires MI
- [[agentic-ai-radiology]] (#069) — agentic AI framework where MI ensures each agent's reasoning is auditable

### Agent & Memory Architecture
- [[memento-llm-agents-without-finetuning]] (#033) — memory-based learning could enable TCM-specific experience accumulation without retraining
- [[magentic-ui-human-in-loop]] (#013) — HITL design requires that AI reasoning be interpretable to human practitioners

## Related Concepts
- [[Mechanistic Interpretability]] — core concept
- [[AI Transparency]] — MI is the technical pursuit of transparency
- [[AI Safety and Alignment]] — safety depends on understanding model internals
- [[Medical AI]] — domain application
- [[AI Hallucination]] — MI can explain causal origins of hallucination

## Sibling Projects
- [[AI x TCM Research Agenda]] — broader research agenda; MI for TCM is the deepest technical component
- [[EL470 Publication Strategy]] — MI findings could yield publications on AI interpretability in medical education

## Gaps & Next Steps
- Test persona vector extraction on TCM-specific traits (holistic reasoning, pattern differentiation)
- Benchmark hallucination patterns on TCM clinical vignettes (adapt adversarial hallucination methodology from #029)
- Explore SAE decomposition of TCM concept representations
- Connect with [[Anthropic]]'s MI research community for methodology guidance
- From [[gap-analysis]]: non-Western AI knowledge representation is a HIGH priority gap directly addressed by this project
