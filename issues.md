# issues.md -- PMAO Agent

Append only. Captures unclear instructions, illegible sources, ambiguous rules, OCR errors, naming conflicts, scope gaps. Pairs with skill PMAO-10 issue_capture.

---

## Purpose

Any time the agent encounters source material it cannot fully parse, an instruction that admits multiple interpretations, or a rule that contradicts another rule: log here immediately. Do not silently resolve. Do not assume. Surface for Sage.

---

## Severity Legend

| Tag | Meaning |
|-----|---------|
| BLOCK | Cannot proceed without resolution. |
| WARN | Can proceed with flagged assumption. |
| NOTE | Cosmetic or future-fix. |

---

## Format

`ID | YYYY-MM-DD | severity | source | issue | proposed_fix | status`

Status values: OPEN, RESOLVED, DEFERRED.

---

## Open Issues

| ID | Date | Sev | Source | Issue | Proposed Fix | Status |
|----|------|-----|--------|-------|--------------|--------|
| I-01 | 2026-04-26 | WARN | system_directive_protocol.png Section 5 | Sub-evaluator labels in Trinity panel not all legible. metrics_ledger v3 uses synthesized labels (L_src, L_inf, L_evd, P_int, P_scp, P_msn, E_fmt, E_tone, E_pref). | Sage to confirm canonical labels or approve v3 synthesis. | OPEN |
| I-02 | 2026-04-26 | WARN | Rubric_Correction_Justification_Guide.png | OCR-style typos in source image: "Buadind" likely "Bundled", "froow" likely "flow", "Whef" likely "What", "rone" likely "tone", "spees" likely "specs", "nurror" likely "mirror", "rope" likely "tone". Used inferred meanings in v3 Rubric Architect block. | Confirm interpretations or supply clean source. | OPEN |
| I-03 | 2026-04-26 | NOTE | spec.md OQ-01 | Pass 2 corpus scope undefined for software-engineering/architecture-design. | Sage decision. | OPEN |
| I-04 | 2026-04-26 | NOTE | spec.md OQ-02 | Pass 2 inclusion of knowledge-graphs RAG titles undecided. | Sage decision. | OPEN |
| I-05 | 2026-04-26 | NOTE | spec.md OQ-03 | research_papers/ sub-folder structure undecided (papers vs books separation). | Sage decision. | OPEN |
| I-06 | 2026-04-26 | NOTE | spec.md OQ-04 | rubric_engineering/ as fourth domain sub-folder undecided. | Sage decision. | OPEN |
| I-07 | 2026-04-26 | NOTE | system_directive.md history | "143_Protocol" deprecated name still referenced in some library audit docs. Rename-on-contact rule exists but no enforcement scan run. | Run rename pass when corpus indexing begins. | OPEN |
| I-08 | 2026-04-26 | NOTE | metrics_ledger.md | Full per-sub-evaluator column schema deferred until first scored row. May cause column drift if scored before lock. | Lock full schema before first Trinity scoring run. | OPEN |
| I-09 | 2026-04-26 | NOTE | bundle delivery | Sage_Agent_Prompt_Engineer_bundle_v1.zip standalone auto-builder content not yet ingested. Drops next turn. | Ingest on receipt. Cross-reference for skill drafts. | OPEN |
| I-10 | 2026-04-26 | NOTE | naming | Agent name "PMAO" not yet validated as canonical short form. Could become Sage_Agent_Prompt_Engineer per bundle name. | Sage to confirm naming on bundle ingest. | OPEN |

---

## Resolved / Deferred

*(empty)*

---

## Triage Cadence

- Sage reviews issues.md at session start if any open BLOCK exists.
- WARN items reviewed at session boundaries.
- NOTE items reviewed at corpus-pass milestones.

---

## Capture Rule (PMAO-10 reference)

Trigger: any of the following auto-creates an issue row.
1. Source contains illegible text (image, scan, OCR errors).
2. Instruction admits two or more interpretations.
3. Rule X conflicts with rule Y in same canon set.
4. Required input is missing and proceeding requires a default.
5. Source class is unknown or outside the approved 5.

The agent never silently resolves. Log the issue, flag severity, propose fix, surface to Sage.

---

*issues.md v1 | 2026-04-26 | 10 open issues seeded from v3 rewrite session*
