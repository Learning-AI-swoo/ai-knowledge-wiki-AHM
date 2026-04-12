---
title: Mechanistic Interpretability
aliases: [MI, Mech Interp, Model Internals]
sources: 1
last_updated: 2026-04-11
tags: [Technical, Research, Safety]
---

# Mechanistic Interpretability

## Definition
The study of AI model internals — understanding how neural networks represent, process, and transform information at the level of individual neurons, attention heads, and activation patterns, with the goal of making AI behavior predictable and controllable.

## Key Arguments
[[persona-vectors-character-traits|The Persona Vectors paper]] demonstrates a practical application of interpretability: extracting linear directions in activation space that correspond to character traits, then using these vectors for monitoring, steering, and preventive control. This approach — identifying meaningful directions in high-dimensional activation spaces — is a core technique of mechanistic interpretability.

The paper's use of Sparse Autoencoders (SAE) to decompose persona vectors into fine-grained features (e.g., "evil" → profanity, hacking, torture sub-features) shows how interpretability can provide granular understanding of model behavior.

## Related Sources
- [[persona-vectors-character-traits]] — persona vectors as applied mechanistic interpretability

## Related Concepts
- [[AI Safety and Alignment]]
- [[AI Transparency]]
- [[Medical AI]]
- [[AI Hallucination]]

## Sung's Project Connections
- [[Mechanical Interpretability for TCM]] — **core concept**: Sung's research project directly applies MI techniques to TCM domain; persona vector techniques may be adaptable to Sung's activation patching work

## Gaps / Further Investigation
- Scaling MI techniques to larger models
- Domain-specific interpretability (medical reasoning, clinical judgment)
- Causal vs. correlational interpretability methods
- Practical tools for MI research (TransformerLens, SAE libraries)
