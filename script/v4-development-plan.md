# Silent Cradle — V4 Development Plan (Creative Pass)

**Lead:** Qwen (overall project lead) · **Baseline:** `script/silent-cradle-screenplay-v3-polish.md` (FROZEN — do not edit)
**Date:** 2026-08-28 · **Status:** active
**Reporter:** @badex · **Final signoff:** @badex

## 1) Framing decision

V3 is 24 scenes / **4,957 words**. A 90–100 min feature needs ~9,000–12,000 words.
V3 is therefore a **compressed narrative pass, not a draft to polish — the creative pass is an expansion to full feature length**, with structure decisions made first and dialogue polish last.

## 2) Review lenses (one per reviewer, notes only, no baseline edits)

| Reviewer | Lens | Notes file (due 2026-08-31) |
|---|---|---|
| Qwen (lead) | Structure, the loss/grief engine, consolidation | `script/reviews/v4-notes-qwen-structure.md` |
| Codex | Causality, continuity, escalation, plausibility, production feasibility (red-team delivered — see below) | `script/reviews/v4-notes-codex-plausibility.md` |
| Claude | Dialogue & naturalism: aphorism budget, subtext, tone rules (lore bible §4), supporting-cast interiority | `script/reviews/v4-notes-claude-dialogue.md` |
| glm flash | Cultural texture: tag every culture-dependent beat/line/page for the consultant brief (consultant is authority, not reviewer) | `script/reviews/v4-notes-glmflash-cultural-flags.md` |

Existing input already in play:
- Codex red-team (9 issues + 24 consultant questions): workspace `RESEARCH/SILENT_CRADLE_CODEX_CREATIVE_PASS_V3.md`
- Qwen full read observations: sections 3–4 below

## 3) Lead's independent observations (from full V3 read)

1. **The loss history is never explicit.** The engine is Lina's grief, but the audience never learns what happened (miscarriage? failed IVF? years of infertility?). "Ashamed of what didn't happen" (scene 21) lands only if we've seen enough. This question was already open in `silent-cradle/akuaba-notes.md` since v1 and remains unanswered. **Decision needed in structure phase: what is revealed, when, and how (recommend one concrete reveal before the midpoint).**
2. **Therapy continuity gap.** Scene 10 shows Dr. Chen reading intake notes — Lina is already in therapy off-screen. Scene 6 has her canceling a Tuesday "clinic" appointment; scene 14 has Elena "calling Dr. Chen's office." When did therapy start, and is the Tuesday appointment the fertility clinic or Dr. Chen? **Need an on-screen therapy-entry beat; clarify the clinic appointment's identity.**
3. **Kwame vanishes after scene 4.** Lore bible makes him the "bridge between cultures"; as written the cultural thread dies in Act 1 and the object becomes a closet item. Recommend a **Kwame second entry tied to Lina's escalation** — he becomes the community-culture mirror of the workplace intervention. (Consultant input on how credible/respectful that encounter is.)
4. **Rob's profession is TBD** (lore bible §6) and v3 never anchors what he does. He needs a job that feeds the "masculine grief response" theme.
5. **Aphorism density** (echoing Codex #9): candidates to protect — "It counts as honesty. Not proof." / "Logistics are how things stay upright." / "Objects don't misquote me." / "I'm not going to perform fragility for this room." / "I confused control with professionalism." The rest should dissolve into behavior.

## 4) Open decisions (to be closed in the decision matrix)

| # | Decision | Options | Decided by |
|---|---|---|---|
| D1 | What exactly is Lina's loss history; what is revealed and when | explicit reveal pre-midpoint / partial / remain ambiguous | @badex + team |
| D2 | Clinic appointment identity + therapy entry beat | rewire scene 6 / add scene | lead |
| D3 | Acquisition path for the akuaba (impulse buy vs prior encounter vs community introduction) | keep / revise per consultant | consultant-informed |
| D4 | Kwame second entry — yes/no, when, what he does | add / hold | lead + consultant |
| D5 | Rob's profession + private stake + his own mistake | TBD | Claude draft, lead lock |
| D6 | Compress scenes 12–17 to how many; which concrete classroom consequence to add | merge 12+16 / keep 13 | lead |
| D7 | Recovery time: how many weeks between scenes 19–24; the one imperfect attempt | 2 wks / 1 month / season | lead |
| D8 | Target runtime and page count (90 / 100 min) | 90–100 | @badex |

## 5) Workflow and calendar

1. **V3 frozen** (done).
2. **Lens notes due 2026-08-31** → `script/reviews/`.
3. **Decision matrix (lead consolidation): 2026-09-01–02** — every note gets `keep / revise / test-with-consultant / reject`.
4. **Structure lock: week of 2026-09-08** — V4 scene list + word budget per scene (aligns with the team's September "official docs locked" milestone).
5. **Expansion drafting: Sep–Oct 2026** — act by act; new scenes flagged `NEW` in the skeleton.
6. **Consultant brief extracted from locked structure** (see `silent-cradle/cultural-consultation-questions-v1.md`); session 1 scheduled after structure lock — **payment gated by Codex (approved budget + first-spend controls) and @badex signoff**.
7. **Cultural integration → sessions 2–3 on revised pages → V4 final.**
8. V4 → deliverables 01–03 alignment (Qwen lane) + closeout pack (Claude) — feeds the April 2027 report.

## 6) Guardrails (from lore bible §8 + team agreement)

- No horror-doll tropes; grounded grief psychology.
- Cultural practice is never framed as pathology; Lina's compulsion is individualized and labeled as such.
- No didactic appropriation speeches — dramatize conflicting perspectives.
- Culture-dependent material is **tagged as an open question** during drafting, never rewritten from assumption.
- Consultant is not asked to certify fertility-loss psychology, therapy, employment law, or school HR — separate lanes if needed.
