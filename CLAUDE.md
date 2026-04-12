# CLAUDE.md — AI Knowledge Wiki 운영 매뉴얼

이 vault는 Sung의 AI 큐레이션 컬렉션(84개)을 컴파일한 Karpathy-style LLM Wiki다.

## Vault 구조

| 폴더 | 용도 |
|---|---|
| `raw/` | 원본 자료. **수정 금지.** |
| `concepts/` | 개념 페이지 — 위키의 핵심. 여러 원문을 주제별로 묶음. |
| `sources/` | 원문별 요약 페이지. 개념/엔티티 위키링크 포함. |
| `entities/` | 인물(`people/`), 기관(`organizations/`), 도구(`tools/`). |
| `projects/` | Sung의 연구/프로젝트 아이디어. |
| `brain/` | 상위 컨텍스트 (VUIM AI Lab 우산 문서). |
| `synthesis/` | 교차 분석, 갭 분석, 테마 맵. |
| `outputs/` | 쿼리/분석 결과물. |

## 링크 규칙

- 모든 페이지는 최소 2개 이상의 다른 페이지와 `[[위키링크]]`.
- 첫 등장 시에만 링크. 같은 페이지 내 반복 링크 금지.
- Obsidian `[[wikilink]]` 형식 사용.

## 언어

- 위키 본문은 영어.
- Sung's Note가 한국어인 경우 원문 보존하되, 요약은 영어로.

## 원문 보호

- `raw/` 폴더 파일은 절대 수정하지 않는다.
- 해석/분석은 `sources/` 또는 `concepts/`에 작성.

## 태그 체계

기존 (노션 CSV): Teaching and Learning, Technical, Medical, Ethics, Safety, AI Strategy, Policy, Regulation, Prompt Engineering, Research, Use Case, Tools, DEI, Philosophy

추가: Assessment, Cognitive Science, Knowledge Management

## 로그

- 모든 작업을 `log.md`에 기록.
- 형식: `## [YYYY-MM-DD] action | description`

## 개념 페이지 템플릿

```markdown
---
title: [concept name]
aliases: [alternate terms]
sources: [number of related sources]
last_updated: [date]
tags: [tags]
---

# [Concept Name]

## Definition
[1-2 sentence definition]

## Key Arguments
[What the sources say. Consensus, debates, contradictions.]

## Related Sources
- [[source-title]] — [one-line summary]

## Related Concepts
- [[other-concept]]

## Sung's Project Connections
- [[project-name]] — [how it connects]

## Gaps / Further Investigation
[Areas not covered by the collection]
```

## Sung의 프로젝트 (연결 우선순위)

1. Mechanical Interpretability for TCM
2. EL470 Publication Strategy
3. AI Champion Micro-Credential
4. AI x TCM Research Agenda

위키 컴파일 시 원문과 이 프로젝트들 간 연결을 적극적으로 찾는다.

## 배치 처리

- 84개를 한꺼번에 처리하지 않는다. 10-15개씩 배치.
- 각 배치 후 `index.md`, `log.md` 업데이트.
