---
title: LLM Benchmarks
aliases: [AI Benchmarks, Model Evaluation, AI Evaluation]
sources: 2
last_updated: 2026-04-11
tags: [Technical, Research, Safety]
---

# LLM Benchmarks

## Definition
Standardized evaluation frameworks used to measure LLM capabilities across dimensions like language understanding, reasoning, safety, and domain-specific knowledge — serving as both performance metrics and development direction indicators.

## Key Arguments
Two complementary critiques emerge:

1. **Structural survey** ([[llm-benchmarks-survey|283-benchmark survey]]): benchmarks evolved from simple accuracy (GLUE) to dynamic, multilingual, process-oriented evaluation (LiveBench), but face fundamental problems — data leakage, cultural bias, static assessment. Future benchmarks need dynamism, causality, inclusivity, and robustness.

2. **Incentive problem** ([[understanding-mitigating-ai-hallucinations|OpenAI hallucination research]]): benchmarks structurally incentivize guessing over admitting uncertainty. This creates a vicious cycle where even more capable models continue hallucinating because that's what scores best. The fix is socio-technical: change scoring to penalize falsehoods more than uncertainty.

## Related Sources
- [[llm-benchmarks-survey]] — 283 benchmarks categorized and analyzed
- [[understanding-mitigating-ai-hallucinations]] — benchmark scoring incentivizes hallucination

## Related Concepts
- [[AI Hallucination]]
- [[AI Safety and Alignment]]
- [[AI in Education]]
- [[Mechanistic Interpretability]]

## Gaps / Further Investigation
- Domain-specific benchmark design for medical, legal, educational AI
- Dynamic, living benchmarks vs. static evaluation
- Benchmark design that rewards appropriate uncertainty expression
