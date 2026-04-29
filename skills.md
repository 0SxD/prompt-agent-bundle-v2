# skills.md -- PMAO Agent

Tree index. Pointers only. Load when skill needed.

---

## Read Protocol

1. Load this file.
2. Find skill ID + path.
3. Load the sub-skill .md.
4. Follow it.

PENDING_DRAFT skill = flag, route to issues.md, queue draft. Do not fabricate process.

---

## Status Legend

| Status | Meaning |
|--------|---------|
| PENDING_DRAFT | ID seeded, content not written. |
| DRAFT | Written, not validated. |
| VALIDATED | Tested in real session at Trinity 15. |
| DEPRECATED | Replaced. Mark successor ID. |

---

## Population Rule

Skills written ONLY after a real task failure OR Trinity gate fire on same weakness twice. No speculative pre-population. Each creation logged in COMPACTION_LEDGER.

---

## PMAO Skills

| ID | Skill | Path | Status | Source |
|----|-------|------|--------|--------|
| PMAO-01 | prompt_pattern_extract | skills/prompt_pattern_extract.md | PENDING_DRAFT | Domain |
| PMAO-02 | system_directive_write | skills/system_directive_write.md | PENDING_DRAFT | Domain |
| PMAO-03 | multi_agent_coordination_pattern | skills/multi_agent_coordination_pattern.md | PENDING_DRAFT | Domain |
| PMAO-04 | chain_of_thought_analysis | skills/chain_of_thought_analysis.md | PENDING_DRAFT | Domain |
| PMAO-05 | rubric_evaluation | skills/rubric_evaluation.md | PENDING_DRAFT | Domain |
| PMAO-06 | wiki_entry_write | skills/wiki_entry_write.md | PENDING_DRAFT | Domain |
| PMAO-07 | rubric_architect | skills/rubric_architect.md | PENDING_DRAFT | v2 synthesis |
| PMAO-08 | quarantine_review | skills/quarantine_review.md | PENDING_DRAFT | v2 synthesis |
| PMAO-09 | trinity_gate_application | skills/trinity_gate_application.md | PENDING_DRAFT | v2 synthesis |
| PMAO-10 | issue_capture | skills/issue_capture.md | PENDING_DRAFT | v3 synthesis |

---

## Cross-Reference

- PMAO-05 evaluates rubrics. PMAO-07 writes them. Keep distinct.
- PMAO-09 is meta: every skill calls it on completion. Draft first when first real gate fires.
- PMAO-10 owns issues.md write surface. Auto-fires on any unclear instruction or illegible source.

---

*skills.md v3 | 2026-04-26 | 10 skills seeded, all PENDING_DRAFT*
