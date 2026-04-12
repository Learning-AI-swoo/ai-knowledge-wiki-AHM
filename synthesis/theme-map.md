---
title: Theme Map — Cross-Cutting Relationships
last_updated: 2026-04-11
sources_analyzed: 78
---

# Theme Map

A structural map of how the 16 concepts, 78 sources, and 4 projects interrelate across Sung's AI Knowledge Wiki.

---

## Core Concept Clusters

### Cluster 1: Medical AI Ecosystem (21 sources)
The largest and densest cluster. [[Medical AI]] is the gravitational center, connected to nearly every other concept.

```
                    ┌─────────────────────┐
                    │     Medical AI      │ ← 21 sources
                    │  (diagnostics,      │
                    │   policy, tools)    │
                    └──────┬──────────────┘
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
  ┌─────▼─────┐    ┌──────▼──────┐    ┌──────▼──────┐
  │ AI Hallu-  │    │ Human-in-  │    │ AI Regula-  │
  │ cination   │    │ the-Loop   │    │ tion &      │
  │ (5 src)    │    │ Systems    │    │ Policy      │
  └─────┬──────┘    │ (2 src)    │    │ (6 src)     │
        │           └──────┬─────┘    └──────┬──────┘
        │                  │                 │
        └──────────┬───────┘                 │
                   │                         │
            ┌──────▼──────┐          ┌───────▼──────┐
            │ AI Safety & │◄─────────│ Korea AI     │
            │ Alignment   │          │ Basic Act    │
            │ (3 src)     │          │ (#066-067)   │
            └─────────────┘          └──────────────┘
```

**Key tools**: [[MAI-DxO]], [[g-AMIE]], [[MedGemma]], [[OpenEvidence]], [[MultiverSeg]]
**Key people**: [[Eric Topol]]
**Project link**: → [[AI x TCM Research Agenda]] (28+ connections)

---

### Cluster 2: AI & Learning / Cognition (14 + 5 sources)
The second-largest cluster bridges education and cognitive science.

```
  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
  │ AI in        │◄───►│ Cognitive    │◄───►│ AI Literacy  │
  │ Education    │     │ Debt         │     │              │
  │ (14 src)     │     │ (5 src)      │     │ (5 src)      │
  └──────┬───────┘     └──────┬───────┘     └──────┬───────┘
         │                    │                    │
         │            ┌──────▼───────┐             │
         └───────────►│ Metacognitive│◄────────────┘
                      │ Laziness     │
                      │ (#062)       │
                      └──────────────┘
```

**Key tension**: AI improves product quality but not learning process (Fan et al.)
**Sung's insight**: System 1/2 confusion — AI chatbot speed collapses slow metacognitive assessment into fast heuristic response
**Project links**: → [[EL470 Publication Strategy]], [[AI Champion Micro-Credential]]

---

### Cluster 3: AI Agents & Workforce (7 + 7 sources)
Agents as operational infrastructure meet employment impact.

```
  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
  │ AI Agents    │────►│ AI and       │◄────│ Cognitive    │
  │ (7 src)      │     │ Employment   │     │ Debt         │
  └──────┬───────┘     │ (7 src)      │     └──────────────┘
         │             └──────┬───────┘
         │                    │
  ┌──────▼───────┐    ┌──────▼───────┐
  │ Context      │    │ Workslop     │
  │ Engineering  │    │ (#042, #071) │
  │ (2 src)      │    └──────────────┘
  └──────┬───────┘
         │
  ┌──────▼───────┐
  │ Prompt       │
  │ Engineering  │
  │ (4 src)      │
  └──────────────┘
```

**Key finding**: AI wins speed/cost (88%/96%), humans win quality. Hybrid teaming +69% efficiency.
**Moltbook warning**: "Golden Time" — while agents use natural language, we can monitor; vector-space communication will make this impossible.

---

### Cluster 4: Technical Foundations (interpretability, transparency, benchmarks)

```
  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
  │ Mechanistic  │◄───►│ AI           │◄───►│ AI Safety &  │
  │ Interpret-   │     │ Transparency │     │ Alignment    │
  │ ability (1)  │     │ (3 src)      │     │ (3 src)      │
  └──────┬───────┘     └──────────────┘     └──────┬───────┘
         │                                        │
         │             ┌──────────────┐            │
         └────────────►│ LLM          │◄───────────┘
                       │ Benchmarks   │
                       │ (2 src)      │
                       └──────────────┘
```

**Key insight**: OpenAI proved benchmarks structurally incentivize hallucination. The fix is socio-technical (change scoring), not just technical.
**Project link**: → [[Mechanical Interpretability for TCM]]

---

## Cross-Cluster Bridges

These sources connect multiple clusters and are the highest-value nodes in the wiki:

| Source | Clusters Connected | Why It Matters |
|---|---|---|
| [[adversarial-hallucinations-medical-ai]] (#029) | Medical + Safety + Technical | 65.9% hallucination rate; prompt engineering as defense |
| [[navigating-ai-era-collaboration]] (#018) | Agents + Cognition + Employment | Human bottleneck framework; exploration vs. exploitation |
| [[state-of-clinical-ai-2026]] (#060) | Medical + Benchmarks + Agents + HITL | "Jagged frontier": superhuman on controlled tasks, brittle on uncertainty |
| [[ai-future-education-unesco]] (#040) | Education + Policy + Cognition + Equity | AI as catalyst for educational goals, not technology showcase |
| [[karpathy-llm-knowledge-base-workflow]] (#076) | Technical + Agents + Knowledge Mgmt | Direct inspiration for this wiki project |
| [[future-ai-healthcare-conflicts]] (#010) | Medical + Policy + Employment + Sovereignty | "Costly coexistence trap" and geopolitical AI sovereignty |

---

## Project Connection Map

```
┌────────────────────────────┐
│  Mechanical Interpretability│◄── Persona Vectors (#012)
│  for TCM (Priority 1)      │◄── CoT Monitoring (#007)
│                             │◄── Memento (#033)
└──────────────┬─────────────┘
               │ (shares MI/safety themes)
               │
┌──────────────▼─────────────┐
│  AI x TCM Research Agenda  │◄── 28+ sources
│  (Priority 4)              │◄── MedGemma TCM use (#041)
│                             │◄── Korea AI Basic Act (#066)
│                             │◄── Agentic Radiology (#069)
└────────────────────────────┘

┌────────────────────────────┐
│  EL470 Publication Strategy│◄── Credibility threshold (#046)
│  (Priority 2)              │◄── Metacognitive laziness (#062)
│                             │◄── UNESCO assessment (#040)
└────────────────────────────┘

┌────────────────────────────┐
│  AI Champion Micro-Credential│◄── Literacy redefined (#065)
│  (Priority 3)               │◄── AI job interview (#051)
│                              │◄── OpenAI certification (#034)
│                              │◄── Equity crisis (#073)
└──────────────────────────────┘
```

---

## Temporal Arc

The 78 sources span July 2025 to April 2026. The collection reveals an arc:

1. **Mid-2025**: Technical foundations — ICL mechanisms, CoT monitoring, persona vectors
2. **Late 2025**: Medical AI explosion — MAI-DxO, MedGemma, OpenEvidence, adversarial hallucination
3. **Early 2026**: Societal reckoning — workslop, AI burnout, metacognitive laziness, equity crisis, survivor's guilt
4. **Spring 2026**: Synthesis — Karpathy's knowledge base workflow, agentic radiology, Korea regulation, this wiki

The collection moves from **"what AI can do"** → **"what AI does to us"** → **"how we should respond"**.
