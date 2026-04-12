---
title: AI Hallucination
aliases: [Hallucination, LLM Hallucination, Confabulation]
sources: 5
last_updated: 2026-04-11
tags: [Safety, Ethics, Technical, Research]
---

# AI Hallucination

## Definition
The generation of plausible-sounding but factually incorrect, fabricated, or nonsensical outputs by AI models — a fundamental reliability challenge across all LLM applications.

## Key Arguments
Hallucination manifests differently across contexts. [[anthropic-llm-vending-experiment|Anthropic's Project Vend]] showed practical hallucinations: emailing fictional entities, scheduling impossible meetings — failures of common sense, not just factual accuracy. The [[future-ai-healthcare-conflicts|Korean healthcare analysis]] identifies hallucination as a critical barrier to medical AI adoption, noting it creates legal and ethical dilemmas around accountability.

[[using-ai-right-now-quick-guide|Ethan Mollick]] offers practical advice: hallucinations are less frequent with larger models and web search, but no model is immune. Users should start with familiar topics to calibrate their trust.

## Related Sources
- [[anthropic-llm-vending-experiment]] — practical hallucination failures in business context
- [[future-ai-healthcare-conflicts]] — hallucination as a barrier to medical AI adoption
- [[adversarial-hallucinations-medical-ai]] — 65.9% hallucination rate on adversarial clinical vignettes; prompt engineering most effective mitigation; distillation degrades safety
- [[adversarial-hallucination-vulnerability-medical-ai]] — same study with additional sovereignty/control perspective
- [[understanding-mitigating-ai-hallucinations]] — OpenAI: root cause is benchmark scoring that rewards guessing over uncertainty

## Related Concepts
- [[AI Safety and Alignment]]
- [[Medical AI]]
- [[AI Transparency]]
- [[Prompt Engineering]]
- [[LLM Benchmarks]]

## Sung's Project Connections
- [[AI x TCM Research Agenda]] — hallucination mitigation is critical for any clinical AI application

## Gaps / Further Investigation
- Hallucination rates across medical specialties
- Effective detection and mitigation strategies for clinical contexts
- Relationship between hallucination and model interpretability
