# metrics_ledger.md -- PMAO Agent

Append only. Never summarize. Never load to HOT_CACHE.

Schema v2: trinity scoring uses 3x3 sub-evaluators (each 0/1/2, pillar capped at 5).

---

## Sub-Evaluator Index (DRAFT)

| Pillar | Sub-1 | Sub-2 | Sub-3 |
|--------|-------|-------|-------|
| Logos (L) | L_src: source citation | L_inf: inference auditable | L_evd: evidence class tagged |
| Pathos (P) | P_int: intent matched | P_scp: scope honored | P_msn: mission served |
| Ethos (E) | E_fmt: format met | E_tone: tone met | E_pref: preferences applied |

Labels are draft. See issues.md I-01. Confirm with Sage before validation pass.

---

## Ledger

| timestamp | session | agent | task | model | in_tok | out_tok | usd | L | P | E | total | gate | iter | qrt | notes |
|-----------|---------|-------|------|-------|--------|---------|-----|---|---|---|-------|------|------|-----|-------|
| 2026-04-24 | s00 | SYSTEM | scaffold + intake_1 | n/a | 0 | 0 | 0.00 | - | - | - | - | INIT | 0 | 0 | 5 core + 4 corpus files |
| 2026-04-25 | s01 | PMAO | v2 rewrite | claude-opus-4-7 | est | est | est | - | - | - | - | INIT | 0 | 0 | governance v1->v2 |
| 2026-04-26 | s02 | PMAO | v3 tighten + issues.md | claude-opus-4-7 | est | est | est | - | - | - | - | INIT | 0 | 0 | governance v2->v3, PMAO-10 added |

Per-sub columns expand on first scored row (Trinity 15 attempt). Lock full schema before scoring.

---

*metrics_ledger.md v3 | 2026-04-26 | compacted, full schema deferred to first scored row*
