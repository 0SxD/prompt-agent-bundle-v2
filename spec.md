# spec.md -- PMAO Agent

zero_bloat: HOT_CACHE overwrite only, 500 word cap. Insights -> INSIGHTS_LEDGER. Tasks -> TASK_QUEUE. Costs -> metrics_ledger. Unverified -> QUARANTINE. Confusion -> issues.md.

---

## HOT_CACHE

```
STATUS: v3 governance bundle deployed. Awaiting Sage approval + corpus pass 2 scope.

SESSION_TYPE: file shortening + issue_capture skill addition.

CHANGES_v3:
- All 5 governance files tightened ~30-50%.
- Trinity 3x3 sub-evaluators referenced not expanded (lives in metrics schema).
- New file: issues.md for confusion/illegibility tracking.
- New skill: PMAO-10 issue_capture.

ACTIVE_TASK: T01 -- Sage v3 deployment approval.

ACTIVE_VARS:
- corpus_subs: prompt_engineering, multi_agent_systems, llm_orchestration
- intake_pass: 1 of N
- skills: 10 PENDING_DRAFT
- directive_version: v3
- trinity: 15=PROCEED, 10-14=LOOP_BACK, <10=BLOCK
- quarantine_aging: 30 days
- issues_open: see issues.md

CONFIDENCE: TRUE=v3 governance. FALSE=skills content. PENDING=pass 2 scope, OQ resolution.

NEXT: Sage decides (a) accept v3, (b) resolve OQs, (c) begin prompt engineering corpus ingest.
```

---

## GRAPH_LINKS

| File | Path | Status |
|------|------|--------|
| bootstrap.md | ./bootstrap.md | LIVE v3 |
| spec.md | ./spec.md | LIVE v3 |
| skills.md | ./skills.md | LIVE v3 |
| system_directive.md | ./system_directive.md | LIVE v3 |
| metrics_ledger.md | ./metrics_ledger.md | LIVE v3 |
| issues.md | ./issues.md | LIVE v1 |
| corpus intake | ./corpus/INTAKE_LOG.md | LIVE |
| pe catalog | ./corpus/prompt_engineering/_index.md | LIVE |
| mas catalog | ./corpus/multi_agent_systems/_index.md | LIVE |
| llmo catalog | ./corpus/llm_orchestration/_index.md | LIVE |
| source: organized_library_v3 | ../../../Corpus_Library_Agentic_Ethos_v1/ | REFERENCE |

---

## COMPACTION_LEDGER

2026-04-24 SCAFFOLD v1: 5 core files + corpus dirs.
2026-04-24 INTAKE_PASS_1: 15 entries from llm-nlp-pt1 + ml-general.
2026-04-25 V2_REWRITE: L1 boot, Quarantine, Trinity 3x3, Rubric Architect added.
2026-04-26 V3_TIGHTEN: governance shortened ~30-50%. issues.md + PMAO-10 added.

---

## TASK_QUEUE

- [ ] T01: Sage v3 deployment approval.
- [ ] T02: Resolve OQ-01/02/03/04. Confirm pass 2 scope.
- [ ] T03: Triage issues.md backlog.
- [ ] T04: Draft PMAO-01 prompt_pattern_extract (on first real failure or gate fire).
- [ ] T05: Draft PMAO-02 system_directive_write.
- [ ] T06: Draft PMAO-07 rubric_architect.
- [ ] T07: Draft PMAO-10 issue_capture.
- [ ] T08: Extract patterns from Raschka 2025.
- [ ] T09: Wiki entry on chain-of-thought prompting.
- [ ] T10: Zero-context Sonnet load test of bootstrap.md v3.

---

## INSIGHTS_LEDGER

*(empty)*

Format: `YYYY-MM-DD | task_id | weakest_pillar | weakest_sub | observation | action`

---

## QUARANTINE

*(empty)*

Format: `YYYY-MM-DD | session | claim | evidence_class | reason | aging_until`

---

## OPEN_Q

- OQ-01: Pull software-engineering/architecture-design (SOLID, C4, Software Architecture Roadmaps) into pass 2?
- OQ-02: Pull knowledge-graphs (Bratanic GraphRAG, Rothman RAG-Driven Generative AI) into pass 2?
- OQ-03: Add research_papers/ sub-folder for ReEvo and Symbolic-Vector Attention Fusion?
- OQ-04: Elevate rubric work to fourth domain sub-folder corpus/rubric_engineering/?

---

## RULES

1. HOT_CACHE: overwrite, 500 words, never append.
2. INSIGHTS_LEDGER, COMPACTION_LEDGER, QUARANTINE, INTAKE_LOG, metrics_ledger, issues.md: append only.
3. TASK_QUEUE: inline status, mark [x] not delete.
4. OPEN_Q: add as OQ-N, mark RESOLVED with answer when closed.
5. system_directive_protocol = identity + loop contract in system_directive.md.
6. Dark psychology + personal school docs: excluded.
7. Stigmergic only: write to artifacts, not peers.
8. Confusion or illegibility: log to issues.md immediately.

---

*spec.md v3 | 2026-04-26 | issues.md added, OPEN_Q list compacted*
