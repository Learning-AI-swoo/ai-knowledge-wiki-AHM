---
title: AI x TCM Research Agenda
status: active
priority: 4
parent: "[[vuim-ai-lab|VUIM AI Lab]]"
last_updated: 2026-04-11
---

# AI x TCM Research Agenda

## Overview
The overarching research agenda exploring the intersection of AI technologies and Traditional Chinese Medicine — including diagnostic AI, clinical decision support, medical imaging, evidence synthesis, and practitioner-AI collaboration models.

With **28+ source connections**, this is the most densely connected project in the wiki and the broadest in scope. While [[Mechanical Interpretability for TCM]] digs deepest into the technical question of how AI processes TCM knowledge, this agenda covers the full landscape: what to build, how to deploy it, and under what regulatory and ethical constraints.

## Priority Research Directions

### Direction 1: TCM Diagnostic AI
**Model**: Adapt [[MAI-DxO]] multi-agent diagnostic approach (#004)
**Approach**: Virtual physician panel with TCM-specific roles — Pattern Differentiation Agent, Herbal Formula Agent, Acupuncture Point Agent, Syndrome Challenger Agent
**Evidence**: MAI-DxO achieved 85% diagnostic accuracy on NEJM cases with 70% cost reduction
**TCM relevance**: pattern differentiation (辨证论治) is inherently a multi-perspective reasoning process; multi-agent architecture is a natural fit

### Direction 2: TCM Medical Image Analysis
**Model**: [[MultiverSeg]] progressive segmentation (#043)
**Approach**: Apply interactive segmentation to TCM diagnostic imaging — tongue diagnosis (舌诊), face diagnosis (面诊), pulse waveform analysis
**Evidence**: MultiverSeg reaches automatic segmentation with only 1-2 manual annotations for X-rays
**TCM relevance**: TCM visual diagnosis is a structured pattern recognition task with established diagnostic criteria; Sung notes "future possibility for TCM medicine image AI"

### Direction 3: TCM Evidence Synthesis
**Model**: [[OpenEvidence]] clinical decision support (#026)
**Approach**: Build a TCM evidence synthesis platform that indexes peer-reviewed TCM literature (PubMed TCM subset, CNKI, TCM-specific databases) and answers clinical questions with evidence grounding
**Evidence**: OpenEvidence scored 90%+ on USMLE, used daily by 40% of US physicians
**Tools**: [[ai-literature-search-tools-biomedical|Literature mining tools]] (#030) for TCM-biomedical connection discovery

### Direction 4: TCM Clinical Intake AI
**Model**: [[g-AMIE]] asynchronous oversight (#009)
**Approach**: AI handles TCM patient intake (symptom collection, lifestyle assessment, constitution classification) while licensed practitioners review and approve diagnosis/treatment
**Evidence**: g-AMIE outperformed early-career physicians in history-taking quality; oversight reduced physician time by 40%
**TCM relevance**: TCM intake (四诊: inspection, auscultation, inquiry, palpation) is extensive and standardizable

### Direction 5: TCM Personal Health Agent
**Model**: [[google-personal-health-agent|Google Personal Health Agent]] (#045)
**Approach**: Multi-agent TCM health system integrating wearable data (heart rate, sleep, activity) with TCM constitution theory for personalized wellness recommendations
**Architecture**: TCM Constitutionalist Agent + Data Analyst Agent + Lifestyle Coach Agent + Orchestrator
**Evidence**: Google's system validated through 7,000+ human evaluations; significant improvements in coaching efficacy

### Direction 6: Regulatory Pathway
**Sources**: [[korea-ai-basic-law-medical]] (#066), [[korea-ai-basic-act-medical-regulation]] (#067), [[promoting-ai-adoption-medical-sector]] (#005), [[us-ai-strategy-try-first]] (#011)
**Challenge**: Korea's AI Basic Act classifies medical AI as "high-risk" with extensive obligations (explanation, disclosure, oversight, 5-year records). TCM-AI systems face additional complexity: is TCM AI a "medical device"?
**Approach**: explore regulatory sandbox / "try-first" pathway for TCM-AI pilots
**Precedent**: [[ai-implementation-chinese-healthcare|China's implementation]] (#027) shows government support is the critical enabler

## Real-World Precedent
**Chang Gung Memorial Hospital (Taiwan)** is already using [[MedGemma]] with Traditional Chinese medical literature (#041). This is the first known instance of a major hospital applying Google's open medical AI models to TCM content — validating that the technical path is viable.

## Source Connections (Complete — 28+)

### Diagnostic AI & Clinical Decision Support
- [[path-to-medical-superintelligence]] (#004) — MAI-DxO multi-agent diagnostic model
- [[physician-centered-oversight-diagnostic-ai]] (#009) — g-AMIE asynchronous oversight
- [[future-ai-healthcare-conflicts]] (#010) — Korean healthcare AI analysis; "costly coexistence trap"
- [[generative-era-medical-ai]] (#025) — Cell paper: six dimensions of healthcare transformation
- [[openevidence-medical-ai-platform]] (#026) — evidence synthesis platform
- [[state-of-clinical-ai-2026]] (#060) — Stanford/Harvard annual report; "jagged frontier"
- [[chatgpt-health-ai-driven-healthcare]] (#059) — ChatGPT Health personal data model
- [[towards-humanist-superintelligence]] (#056) — Microsoft HSI: medical superintelligence as priority
- [[agentic-ai-radiology]] (#069) — agentic AI framework for imaging; HITL mandatory

### Medical Imaging & Tools
- [[medgemma-multimodal-medical-ai]] (#022) — compact multimodal medical model
- [[medgemma-open-models-health-ai]] (#041) — expanded MedGemma; **Chang Gung TCM use**
- [[ai-medical-image-segmentation]] (#043) — MultiverSeg progressive segmentation
- [[google-personal-health-agent]] (#045) — multi-agent personal health system
- [[ai-literature-search-tools-biomedical]] (#030) — 30+ specialized search tools

### Safety & Hallucination
- [[adversarial-hallucinations-medical-ai]] (#029) — 65.9% hallucination rate; prompt engineering defense
- [[adversarial-hallucination-vulnerability-medical-ai]] (#032) — sovereignty/control dimension
- [[ai-healthcare-supervising-supporting]] (#021) — AI monitoring doctors; "quantified workers"

### Policy & Regulation
- [[promoting-ai-adoption-medical-sector]] (#005) — US "try-first" policy
- [[us-ai-strategy-try-first]] (#011) — regulatory sandbox concept
- [[korea-ai-basic-law-medical]] (#066) — Korea AI Basic Act: medical AI as "high-risk"
- [[korea-ai-basic-act-medical-regulation]] (#067) — detailed legal analysis
- [[ai-implementation-chinese-healthcare]] (#027) — China's implementation; government support critical

### Employment & Workforce
- [[generative-ai-occupational-implications]] (#002) — TCM's physical/manual components less susceptible
- [[ai-published-medical-education]] (#046) — credibility threshold in medical AI trust

### Technical Foundations
- [[autonomous-ai-research-agents]] (#023) — Virtual Lab framework for TCM compound research
- [[magentic-ui-human-in-loop]] (#013) — HITL framework; Sung notes "TCM will need this"

## Related Concepts
- [[Medical AI]] — the overarching domain (21 sources)
- [[Human-in-the-Loop Systems]] — TCM clinical practice requires HITL by design
- [[AI Regulation and Policy]] — regulatory frameworks determine what's possible
- [[Mechanistic Interpretability]] — understanding how AI processes TCM concepts
- [[AI Hallucination]] — safety-critical for any clinical AI application
- [[AI Agents]] — multi-agent architectures for TCM diagnostic systems

## Sibling Projects
- [[Mechanical Interpretability for TCM]] — deepest technical component; focuses on model internals
- [[EL470 Publication Strategy]] — TCM-specific credibility or metacognitive studies could combine both projects
- [[AI Champion Micro-Credential]] — TCM-specific AI training modules could be an advanced track

## Gaps & Next Steps
- From [[gap-analysis]]:
  - AI liability/malpractice (HIGH) — needed before any clinical TCM-AI deployment
  - Patient consent in AI care (HIGH) — TCM patient-practitioner relationship at stake
  - Non-Western AI development (HIGH) — TCM is inherently non-Western; sovereign AI matters
- **Immediate**: contact Chang Gung Hospital about MedGemma + TCM collaboration
- **Near-term**: design adversarial hallucination test suite for TCM clinical vignettes (adapt #029 methodology)
- **Medium-term**: prototype TCM diagnostic AI using multi-agent architecture (Direction 1)
- **Long-term**: explore regulatory sandbox for TCM-AI clinical pilots in Korea
