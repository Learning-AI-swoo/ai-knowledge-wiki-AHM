---
title: Context Engineering
aliases: [Context Management, Context Curation]
sources: 2
last_updated: 2026-04-11
tags: [Technical, AI Strategy, Prompt Engineering]
---

# Context Engineering

## Definition
The practice of curating and managing the optimal set of tokens — system prompts, tools, MCP, external data, message history — during LLM inference to maximize desired outcomes. Distinguished from [[Prompt Engineering]] as a broader, iterative discipline focused on the entire context state, not just prompt wording.

## Key Arguments
[[Anthropic]] explicitly positions context engineering as the **natural progression** of prompt engineering ([[context-engineering-ai-agents|context engineering post]]). As agents operate over longer time horizons, the challenge shifts from "what words to use" to "what information should be present at each step." Key insight: context is finite with diminishing returns — an "attention budget" that degrades with scale (context rot).

Three long-horizon techniques emerge: **compaction** (summarizing near window limits), **structured note-taking** (persistent memory outside context), and **sub-agent architectures** (specialized agents returning condensed summaries). [[optimizing-tools-for-ai-agents|Tool optimization]] adds another dimension: tools should be designed for token efficiency, returning high-signal information to minimize context consumption.

## Related Sources
- [[context-engineering-ai-agents]] — Anthropic's definitive post on context engineering
- [[optimizing-tools-for-ai-agents]] — tool design as context engineering

## Related Concepts
- [[Prompt Engineering]]
- [[AI Agents]]
- [[In-Context Learning]]

## Sung's Project Connections
- [[AI Champion Micro-Credential]] — context engineering should be taught alongside prompt engineering

## Gaps / Further Investigation
- Optimal compaction strategies across different domains
- Context engineering metrics and evaluation frameworks
- Interaction between context engineering and model capability scaling
