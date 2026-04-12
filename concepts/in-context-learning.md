---
title: In-Context Learning
aliases: [ICL, Few-Shot Learning, Prompt-Based Learning]
sources: 1
last_updated: 2026-04-11
tags: [Technical, Research, Prompt Engineering]
---

# In-Context Learning

## Definition
The ability of large language models to solve new problems using examples and instructions provided in the prompt, without any parameter updates or fine-tuning — effectively "learning" from context alone.

## Key Arguments
[[understanding-in-context-learning|Google Research]] explains the mechanism: prompts create "implicit weight updates" — the model's internal computations behave as if weights were modified, even though they remain unchanged. This works through efficient rank-1 matrix operations, making it computationally lightweight. The implication is profound: structured prompts can substitute for expensive fine-tuning, especially in data-scarce domains.

## Related Sources
- [[understanding-in-context-learning]] — theoretical foundations of ICL mechanisms

## Related Concepts
- [[Prompt Engineering]]
- [[AI Transparency]]
- [[AI Agents]]

## Sung's Project Connections
- [[AI Champion Micro-Credential]] — understanding ICL is foundational to effective AI use
- [[Mechanical Interpretability for TCM]] — ICL mechanics connect to understanding how models process domain-specific information

## Gaps / Further Investigation
- Limits of ICL: at what complexity does it break down?
- ICL vs. fine-tuning: systematic comparison across domains
- How does ICL interact with model scale?
