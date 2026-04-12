---
title: Prompt Engineering
aliases: [Prompting, Context Engineering]
sources: 4
last_updated: 2026-04-11
tags: [Prompt Engineering, Technical, AI Strategy]
---

# Prompt Engineering

## Definition
The practice of designing and structuring inputs to AI models to achieve desired outputs — ranging from simple task instructions to sophisticated multi-step reasoning frameworks.

## Key Arguments
The theoretical foundation comes from [[understanding-in-context-learning|Google Research's ICL paper]]: well-structured prompts create implicit weight updates, meaning prompt design directly affects model computation — it's not just "asking nicely."

However, [[using-ai-right-now-quick-guide|Ethan Mollick]] argues that with modern models, complex prompting techniques matter less than they used to. Research from Wharton's Generative AI Lab shows politeness doesn't affect quality, and Chain-of-Thought prompting is less impactful than before. What matters more: providing context, being specific, asking for many options, and using branching.

The emerging distinction between **prompt engineering** (crafting individual inputs) and **context engineering** (managing the full information environment) signals an evolution in the field.

## Related Sources
- [[understanding-in-context-learning]] — theoretical basis for why prompts work
- [[using-ai-right-now-quick-guide]] — practical, modern prompting advice
- [[iterative-prompt-design-ai-literacy]] — documented iterative process from naive prompt to codified CustomGPT workflow
- [[adversarial-hallucinations-medical-ai]] — prompt engineering as most effective hallucination mitigation (65.9% → 44.2%)

## Related Concepts
- [[In-Context Learning]]
- [[AI Literacy]]
- [[AI Hallucination]]
- [[Context Engineering]]
- [[AI Agents]]

## Sung's Project Connections
- [[AI Champion Micro-Credential]] — prompt engineering is a core practical skill to teach

## Gaps / Further Investigation
- Prompt engineering vs. context engineering: where is the field heading?
- Domain-specific prompting strategies (medical, educational, research)
- Automated prompt optimization techniques
