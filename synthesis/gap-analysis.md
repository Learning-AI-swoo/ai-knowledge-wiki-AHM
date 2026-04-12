---
title: Gap Analysis — What the Collection Doesn't Cover
last_updated: 2026-04-11
sources_analyzed: 78
---

# Gap Analysis

Systematic identification of topics the 84-item collection does **not** adequately address — areas where additional sources, research, or investigation are needed.

---

## Gap 1: AI Liability and Malpractice Frameworks

**What's present**: The collection discusses medical AI risks extensively (21 sources), including hallucination rates (#029), the "costly coexistence trap" (#010), and the [[state-of-clinical-ai-2026|2026 prediction]] of the first AI malpractice lawsuit.

**What's missing**: No source provides a detailed analysis of **how AI liability actually works** in current legal frameworks. Who is liable when [[MAI-DxO]] misdiagnoses? The physician who followed its recommendation? The hospital that deployed it? The developer? The collection identifies this as a problem (#069 notes "liability remains uncertain") but has no source on existing frameworks, case law, or proposed legislative solutions. [[Korea AI Basic Act|Korea's AI Basic Act]] (#066-067) creates obligations but doesn't resolve the liability chain.

**Why it matters for Sung's projects**: [[AI x TCM Research Agenda]] cannot advance to clinical deployment without understanding the liability landscape. Any TCM-AI system will face these exact questions.

**Recommended investigation**:
- US FDA's Software as a Medical Device (SaMD) liability precedents
- EU AI Act liability proposals (product liability directive updates)
- Comparative analysis: liability in radiology AI vs. diagnostic AI vs. treatment AI
- Insurance models for AI-assisted medical practice

---

## Gap 2: Patient Consent and Autonomy in AI-Assisted Healthcare

**What's present**: [[physician-centered-oversight-diagnostic-ai|g-AMIE]] demonstrates asynchronous physician oversight. [[ai-healthcare-supervising-supporting|NEJM]] raises concerns about "quantified workers." [[chatgpt-health-ai-driven-healthcare|ChatGPT Health]] enables direct patient-AI interaction.

**What's missing**: The collection has **no source on patient consent models** for AI-assisted care. When [[OpenEvidence]] influences a physician's decision, does the patient know? When an Ambient Scribe records a consultation, what consent was obtained? When Utah allows AI to prescribe drugs autonomously (#059), how is patient autonomy preserved? The collection discusses physician oversight extensively but treats the patient as a passive recipient.

**Why it matters for Sung's projects**: [[AI x TCM Research Agenda]] and the broader [[Medical AI]] concept need patient-centered frameworks, not just physician-centered ones. TCM already emphasizes patient-practitioner relationship dynamics.

**Recommended investigation**:
- Informed consent models for AI-assisted diagnosis
- Patient attitudes toward AI in healthcare (survey data)
- Shared decision-making frameworks when AI is involved
- "Right to human decision" policies

---

## Gap 3: Non-English and Non-Western AI Development

**What's present**: [[ai-implementation-chinese-healthcare|China's AI healthcare implementation]] (#027) and [[korea-ai-basic-law-medical|Korea's AI Basic Act]] (#066) provide non-Western perspectives. [[future-ai-healthcare-conflicts|The Korean healthcare essay]] (#010) discusses AI sovereignty.

**What's missing**: The collection is overwhelmingly **US/English-centric** despite Sung's Korea-based perspective and TCM research interests. No source covers:
- Chinese AI models (DeepSeek, Qwen, Baidu) in depth (only mentioned as benchmarks)
- AI development in India, Southeast Asia, Africa, or Latin America
- Multilingual AI capabilities and limitations
- Non-Western ethical frameworks for AI (Confucian, Ubuntu, Buddhist perspectives)
- The [[llm-benchmarks-survey|benchmark survey]] (#031) notes English-centric bias as a problem, but no source addresses solutions

**Why it matters for Sung's projects**: [[Mechanical Interpretability for TCM]] and [[AI x TCM Research Agenda]] operate in a domain where Eastern and Western medical epistemologies intersect. Understanding how AI handles non-Western knowledge systems is foundational.

**Recommended investigation**:
- Chinese sovereign AI strategy and models (DeepSeek ecosystem)
- Multilingual medical AI performance comparisons
- TCM-specific knowledge representation in LLMs
- Non-Western AI ethics frameworks (UNESCO 2025 report touches on this but the collection doesn't extract it)

---

## Gap 4: AI's Impact on Healthcare Employment Specifically

**What's present**: [[AI and Employment]] has 7 sources covering general workforce impacts, and [[Medical AI]] has 21 sources on clinical capabilities. [[future-ai-healthcare-conflicts|The Korean healthcare essay]] (#010) discusses the "value hierarchy reversal" (cognitive labor commoditized; procedural skill becomes premium).

**What's missing**: **No source specifically studies how AI is changing healthcare jobs in practice** — nurse workloads, radiologist displacement data, administrative staff automation, medical school enrollment trends, specialist vs. generalist demand shifts. The collection predicts transformation but lacks empirical data on what's actually happening to healthcare workers.

**Why it matters for Sung's projects**: [[AI x TCM Research Agenda]] needs to understand how TCM practitioners' roles will evolve alongside AI. The [[EL470 Publication Strategy]] could target this gap directly.

**Recommended investigation**:
- Radiology workforce studies post-AI deployment
- Nursing AI augmentation vs. displacement data
- Medical school curriculum changes in response to AI
- TCM practitioner attitudes toward AI (survey research opportunity)

---

## Gap 5: Long-Term Longitudinal Studies on AI and Cognition

**What's present**: [[Cognitive Debt]] has 5 sources identifying short-term effects: reduced brain connectivity (#008), metacognitive laziness (#062), time-saving illusion (#064). Sung's own analysis of System 1/2 confusion is sophisticated.

**What's missing**: **All studies are cross-sectional or short-term experiments**. No source provides longitudinal data (6+ months) on:
- Does cognitive debt accumulate permanently or reverse with intervention?
- How do different AI use patterns (delegation vs. explanation-seeking) affect long-term skill development?
- Do professionals who use AI heavily for 1+ years show measurable skill degradation?
- What are the generational effects (students who grew up with AI vs. those who didn't)?

The [[cognitive-debt-ai-brain|MIT study]] (#008) showed some reversibility when brain-only writers later used AI, but this was a single session, not longitudinal.

**Why it matters for Sung's projects**: [[EL470 Publication Strategy]] could propose or conduct longitudinal studies. [[AI Champion Micro-Credential]] needs evidence-based guidance on "how much AI is too much."

**Recommended investigation**:
- Design longitudinal study: medical students tracked over 2+ years with varying AI use levels
- Existing longitudinal data from calculator/internet adoption (analogous precedents)
- Professional skill degradation studies in other automation contexts (aviation, manufacturing)

---

## Gap 6: AI Assessment and Evaluation in Education

**What's present**: [[AI in Education]] covers pedagogical approaches (14 sources), including process-based assessment (#040), transparency frameworks (#075), and integrity redefinition (#052).

**What's missing**: **No source provides concrete assessment rubrics, grading frameworks, or evaluation tools** that educators can actually use. The collection says "redesign assessment" but doesn't show what redesigned assessment looks like in practice. The [[genai-transparency-framework-education|transparency framework]] (#075) comes closest but addresses disclosure, not grading.

**Why it matters for Sung's projects**: [[AI Champion Micro-Credential]] needs assessment methods. [[EL470 Publication Strategy]] could develop and publish assessment frameworks for AI-integrated medical education.

**Recommended investigation**:
- AI-aware rubric designs for different disciplines
- Process-based portfolio assessment models
- "AI usage disclosure" scoring systems
- Competency-based assessment when AI handles routine knowledge tasks

---

## Gap 7: AI Environmental and Energy Justice

**What's present**: [[environmental-impact-ai|Google's paper]] (#028) argues AI energy impact is manageable through optimization. Sung notes "less than we thought? But how to measure?"

**What's missing**: Only **one source** covers environmental impact, and it's from Google (an interested party). No source addresses:
- Independent energy consumption measurements
- Water usage by data centers
- Environmental justice — who bears the environmental cost of AI?
- The connection between AI education equity (#073) and environmental equity (poorer regions hosting data centers)
- Carbon footprint of training vs. inference at scale

**Relevance**: This is a growing concern that intersects with [[AI Regulation and Policy]] and equity discussions.

---

## Summary: Gap Priority for Sung's Projects

| Gap | Priority | Best Project Fit |
|---|---|---|
| AI Liability/Malpractice | **High** | AI x TCM Research Agenda |
| Patient Consent in AI Care | **High** | AI x TCM Research Agenda |
| Non-Western AI Development | **High** | Mechanical Interpretability for TCM |
| Healthcare Employment Impact | **Medium** | EL470 Publication Strategy |
| Longitudinal Cognition Studies | **Medium** | EL470 Publication Strategy |
| AI Assessment Frameworks | **Medium** | AI Champion Micro-Credential |
| Environmental/Energy Justice | **Low** | (cross-cutting) |
