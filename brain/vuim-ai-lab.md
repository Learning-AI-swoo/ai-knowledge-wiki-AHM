---
title: VUIM AI Lab
aliases: [AI Lab, VUIM Lab]
last_updated: 2026-04-11
---

# VUIM AI Lab

The VUIM AI Lab is Sung's umbrella initiative encompassing AI research, faculty development, student education, and knowledge curation at the intersection of artificial intelligence and health sciences — with a particular focus on Traditional Chinese Medicine (TCM).

This document serves as the top-level context for all projects, programs, and outputs under the Lab.

---

## Mission

To advance AI literacy, medical AI research, and responsible AI integration in health education — grounded in both Western and Eastern medical epistemologies, with TCM as a unique lens.

## Three Pillars

```
┌─────────────────────────────────────────────────┐
│                 VUIM AI Lab                     │
├────────────────┬────────────────┬───────────────┤
│   Research     │   Education    │  Curation     │
│                │                │               │
│ MI for TCM     │ AI Champion    │ AI Knowledge  │
│ AI x TCM       │ Micro-Cred     │ Wiki          │
│ EL470 Pub      │ AI Workshop    │               │
│                │ AI Literacy    │               │
└────────────────┴────────────────┴───────────────┘
```

---

## Research Projects

### 1. [[Mechanical Interpretability for TCM]] — Priority 1
Applying mechanistic interpretability (activation patching, persona vectors, SAE decomposition) to understand how LLMs process TCM domain knowledge. The core question: can we make the "black box" transparent for Eastern medical reasoning?

**Key wiki connections**: [[Mechanistic Interpretability]], [[AI Transparency]], [[AI Safety and Alignment]]
**Strongest source link**: [[persona-vectors-character-traits]] — Sung notes "maybe test it with my Patching work"

### 2. [[EL470 Publication Strategy]] — Priority 2
Strategy for publishing in medical education journals (Medical Education, BMC Medical Education, etc.) with AI-focused clarification research. The shift from "does it work?" to "why does it happen?"

**Key wiki connections**: [[Cognitive Debt]], [[AI in Education]], [[Medical AI]]
**Publication angles identified from wiki**:
- Metacognitive laziness + System 1/2 confusion (#062)
- Credibility threshold: AI warnings don't change student behavior (#046)
- AI as both problem-solver and problem-creator in higher ed (#048)
- UNESCO assessment revolution framework (#040)

### 3. [[AI x TCM Research Agenda]] — Priority 4 (broadest scope)
The overarching research agenda for AI-TCM intersection. With 28+ source connections, this is the most densely connected project in the wiki.

**Key wiki connections**: [[Medical AI]], [[Human-in-the-Loop Systems]], [[AI Regulation and Policy]]
**Priority research directions**:
- TCM diagnostic AI: adapt [[MAI-DxO]] multi-agent diagnostic approach
- TCM image analysis: [[MultiverSeg]] for tongue/pulse/face diagnostics
- TCM evidence synthesis: [[OpenEvidence]] model for TCM literature
- TCM-AI clinical intake: [[g-AMIE]] asynchronous oversight model
- TCM health agent: [[google-personal-health-agent|Google Personal Health Agent]] architecture
- Regulatory pathway: [[korea-ai-basic-law-medical|Korea AI Basic Act]] implications for TCM-AI

**Real-world precedent**: Chang Gung Memorial Hospital (Taiwan) already using [[MedGemma]] with Traditional Chinese medical literature (#041)

---

## Education Programs

### 4. [[AI Champion Micro-Credential]] — Priority 3
A structured credential program for AI literacy targeting faculty and health professionals. Competes in a market increasingly shaped by [[openai-certification-jobs-platform|OpenAI's 10M certification initiative]] (#034).

**Curriculum pillars identified from wiki**


### AI Workshop for Faculty
Faculty-facing training sessions drawing from the wiki's 64 sources tagged for "AI Workshop for Faculty" in the original catalog. Focus areas:
- Practical AI tool selection and use ([[using-ai-right-now-quick-guide]])
- [[Human-in-the-Loop Systems]] design for clinical teaching
- [[Cognitive Debt]] awareness and pedagogical mitigation
- Assessment redesign for the AI era ([[ai-future-education-unesco]])

### AI Literacy for Students
Student-facing foundational AI education, drawing from 26 sources tagged for "AI Literacy for Students." Core themes:
- [[AI Literacy]] — expanded definition: multimodal, conversational, AI-critical
- [[Prompt Engineering]] → [[Context Engineering]] progression
- [[AI Hallucination]] awareness and verification skills
- Responsible AI use ([[genai-transparency-framework-education]])

---

## Knowledge Curation

### AI Knowledge Wiki (This Vault)
A Karpathy-style LLM-compiled wiki of Sung's 84-item AI curation collection. Directly inspired by [[karpathy-llm-knowledge-base-workflow|Andrej Karpathy's LLM Knowledge Base Workflow]] (#076).

**Stats (as of 2026-04-11)**:
- 78 source pages compiled from DOCX originals
- 16 concept pages with ~220 crosslinks
- 25 entity pages (5 people, 10 organizations, 10 tools)
- 4 project pages
- 2 synthesis pages ([[gap-analysis]], [[theme-map]])

**Concept map** (by source density):

| Concept | Sources | Lab Relevance |
|---|---|---|
| [[Medical AI]] | 21 | Core — TCM research, clinical AI |
| [[AI in Education]] | 14 | Core — micro-credential, workshop, literacy |
| [[AI Agents]] | 7 | Emerging — multi-agent research, agentic radiology |
| [[AI and Employment]] | 7 | Context — workforce implications |
| [[AI Regulation and Policy]] | 6 | Critical — Korea AI Basic Act, TCM regulatory pathway |
| [[Cognitive Debt]] | 5 | Core — teaching implications, publication angles |
| [[AI Hallucination]] | 5 | Critical — medical safety, trust thresholds |
| [[AI Literacy]] | 5 | Core — credential design, student programs |

---

## Destination Mapping

The original 84-item catalog tagged each source for specific VUIM destinations:

| Destination | Sources | Wiki Coverage |
|---|---|---|
| VUIM AI Lab | 69 | Discussion, research direction, deep analysis |
| AI Workshop for Faculty | 64 | Practical tools, frameworks, case studies |
| AI Literacy for Students | 26 | Foundational concepts, hands-on guidance |

Many sources span all three destinations, reflecting the Lab's integrated approach.

---

## Open Questions and Gaps

From [[gap-analysis]]:

| Gap | Priority | Lab Response |
|---|---|---|
| AI liability/malpractice | HIGH | Needed for any clinical TCM-AI deployment |
| Patient consent in AI care | HIGH | TCM patient-practitioner relationship at stake |
| Non-Western AI development | HIGH | TCM is inherently non-Western; sovereign AI matters |
| Healthcare employment impact | MEDIUM | Publication opportunity (EL470) |
| Longitudinal cognition studies | MEDIUM | Could design study with VUIM students |
| AI assessment frameworks | MEDIUM | Needed for micro-credential program |

---

## Key People and Partners

**Internal**:
- Sung — Lab director, AI curation, MI for TCM research

**External voices prominent in the wiki**:
- [[Ethan Mollick]] — AI literacy, practical AI guidance
- [[Eric Topol]] — medical AI, generative era of healthcare
- [[Andrej Karpathy]] — LLM knowledge bases, AI-assisted programming
- [[Pilyoung Kim]] — children's AI safety, cognitive development

**Key organizations**:
- [[Google DeepMind]] — MedGemma, g-AMIE, Personal Health Agent
- [[Microsoft Research]] — MAI-DxO, Magentic-UI, Humanist Superintelligence
- [[Anthropic]] — persona vectors, context engineering, tool design
- [[OpenAI]] — hallucination research, ChatGPT Health, certification
- [[UNESCO]] — AI education framework (public purpose, equity, teacher sovereignty)

---

## Temporal Context

The wiki's 78 sources span July 2025 to April 2026. From [[theme-map]], the collection traces an arc:

1. **Mid-2025**: Technical foundations — ICL, CoT monitoring, persona vectors
2. **Late 2025**: Medical AI explosion — MAI-DxO, MedGemma, adversarial hallucination
3. **Early 2026**: Societal reckoning — workslop, burnout, metacognitive laziness, equity crisis
4. **Spring 2026**: Synthesis — this wiki, agentic radiology, Korea regulation

The Lab operates at the intersection of all three phases: building on technical foundations, applying medical AI to TCM, and navigating the societal implications.

---

## Next Steps

1. **Expand wiki** — 6 catalog-only entries (external links) remain unprocessed; new sources to be added as they emerge
2. **Fill gaps** — prioritize AI liability and patient consent research for TCM-AI deployment readiness
3. **Publish** — execute EL470 strategy using wiki-identified angles (metacognitive laziness, credibility threshold)
4. **Build credential** — design AI Champion Micro-Credential using wiki-derived curriculum map
5. **Advance MI research** — test persona vector techniques with Sung's activation patching work
6. **Engage partners** — connect with Chang Gung Hospital re: MedGemma + TCM; explore regulatory sandbox for TCM-AI pilots
