# Review report - B2 Governance, RACI, three lines of defence | 2026-11-08 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Ownership is explicit and the escalation path works: the sponsor cannot overrule a block. Two gaps held it back. The drift row had the reviewer accountable for its own review, and the AI CoE also runs the model gateway the agent depends on. Your answers closed both gaps, and the last [CONFIRM] is resolved.

**Rubric position (indicative, not a prediction):**
| Criterion | Before | After | Marks range before -> after (of 8) |
|---|---|---|---|
| One accountable owner per decision, independent challenge, workable escalation | Partial-Full: R = A on drift row; undeclared gateway link; one [CONFIRM] open | Full (lower) | 5-6 -> 6-7 (Estimate) |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | RACI row 2, A | AI CoE Project Lead -> Head of AI CoE (your answer) | Reviewer check: A is not the role doing the challenge; taught pattern (second-line R, its head A) | Removes "referee their own game" on the one row about challenge |
| 2 | Table 1 row 2 | Added: the AI CoE runs the gateway, so the reviewer sits outside the gateway team and IT security tests the gateway (your answer) | Partial descriptor: weak independence | Declares the conflict and its control, so the marker doesn't find it first |
| 3 | Table 1 row 2 | Tightened wording; "Center" -> "Centre"; dropped "serves as the second-line function" (the field label already says it) | Style; British spelling (config) | Shorter and clearer |
| 4 | Table 1 row 3 | "IRM" spelled out as information risk management; "logical extension of its current digital cadence responsibilities" -> "extends an existing cadence" | Professional usability (quality modifier) | A marker can read it without knowing your organisation's acronyms |
| 5 | Table 1 row 4 | [CONFIRM] removed; generic names kept (your answer) | Completeness | No placeholder left |
| 6 | RACI row 3 | "AI CoE Project Lead (validation reviewer)" -> "validation reviewer" (role already defined) | Consistency X-07 | One name per role across sections |
| 7 | Whole file | [GUIDE] blocks removed; version v3-reviewed | Edit rules | Clean text ready to accept |

## Needs your input
- No [CONFIRM] items remain.

## Judgement flags (not changed)
- **Third line is a risk team, not audit:** Enterprise Risk Support reviews compliance, and in the three-lines model that is closer to second-line work. The course allows proportionate or peer assurance, so this can stand. It is stronger if you add that the team does not report to the Head of Finance or the AI CoE, if that is true. Expect a marker to ask why Internal Audit is not used.
- **AI CoE is close to the platform:** the Head of AI CoE is accountable for drift review and also runs the gateway. For a change to the gateway or model, the CoE reviews its own platform. IT security's test-based block covers part of that. B4 and C3 must not make the AI CoE an owner of agent outcomes.

## Checks
- Arithmetic: not applicable. Length: about 330 words; there is no word budget for B2, and it stays proportionate.
- Consistency: X-07: every A3/B1 role appears (Executive sponsor, function Finance manager, Head of Business-HR, S&A division lead, validation reviewer, Commercial Strategy manager, LT). One A per RACI row. B3 and B4 must reuse "validation reviewer (AI CoE Project Lead)" and "Executive sponsor" as the incident owner. X-17: Hypothetical label kept.
- Evidence: no legal or external claims; no E-ids added.

## Re-review 2026-11-08 (learner edit to v3)
- You added a sentence to Table 1 row 3: Enterprise Risk Support does not report to the Head of Finance or the AI CoE. One edit tightened it: "keeps the review independent of the delivery and funding lines" -> "so it is independent of the funding and validation lines". The AI CoE is the validation line here, not delivery; Strategy & Analytics delivers.
- Effect: the third-line flag is partly resolved. Independence is now stated, and a marker may still ask why Internal Audit is not used. The band stays Full (lower), but the marks range moves to 6-7 of 8 with more confidence (Estimate). Length about 350 words. No [CONFIRM] items. Previous v3 archived as B2_v3-reviewed.bak-20261108-1730.md.

## Next step
- Edit v3 directly if you disagree, then /prompt-accept B2
