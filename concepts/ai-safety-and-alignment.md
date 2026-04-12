---
title: AI Safety and Alignment
aliases: [AI Alignment, AI Safety, Safe AI]
sources: 3
last_updated: 2026-04-11
tags: [Safety, Ethics, Technical, Research]
---

# AI Safety and Alignment

## Definition
The field dedicated to ensuring AI systems behave as intended, remain under human control, and do not cause unintended harm — encompassing monitoring, interpretability, behavioral control, and value alignment.

## Key Arguments
Three complementary approaches emerge from the collection:

1. **CoT Monitoring** ([[monitoring-ai-chain-of-thought|DeepMind]]): Complex tasks force models to reveal genuine reasoning, making CoT-based monitoring effective. But reinforcement learning can teach evasion — monitoring must evolve with AI.

2. **Structural Control** ([[persona-vectors-character-traits|Anthropic]]): Persona vectors enable detection → cause-tracking → prevention → suppression of unwanted personality traits at the activation level. This moves beyond output censorship to internal structural control.

3. **Practical Failure Modes** ([[anthropic-llm-vending-experiment|Anthropic's Project Vend]]): Even simple business tasks expose fundamental gaps in LLM common sense and hallucination tendencies.

The emerging consensus: safety requires multi-layered approaches — transparent reasoning, internal structural controls, and robust monitoring systems evolving alongside model capabilities.

## Related Sources
- [[monitoring-ai-chain-of-thought]] — CoT monitoring and its limits
- [[persona-vectors-character-traits]] — persona vectors for structural control
- [[anthropic-llm-vending-experiment]] — practical failure modes of LLMs

## Related Concepts
- [[AI Transparency]]
- [[AI Hallucination]]
- [[Mechanistic Interpretability]]
- [[Human-in-the-Loop Systems]]
- [[AI Regulation and Policy]]
- [[Medical AI]]

## Sung's Project Connections
- [[Mechanical Interpretability for TCM]] — safety and alignment depend on understanding model internals

## Gaps / Further Investigation
- How do safety measures scale as models grow more capable?
- Interaction effects between different safety approaches (CoT + persona vectors + HITL)
- Safety frameworks specific to medical AI deployment
