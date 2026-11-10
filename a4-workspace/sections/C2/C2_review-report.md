# Review report - C2 Data, privacy, cross-border design | 2026-11-10 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Strong. You resolved all 4 [CONFIRM] items with facts from the organisation: external frontier models via Microsoft Azure in the EU region, zero retention negotiated, logs kept 12 months, cross-border Yes. With these the lifecycle is fully traceable and the transfer risk honest. Edits mainly trimmed length, added the evidence reference for the new organisational facts and removed one apparent contradiction on retention.

**Rubric position (indicative, not a prediction):**
| Criterion | Before (v1) | After (v3) | Marks range before -> after (of 6) |
|---|---|---|---|
| Traceable data -> vendor -> output lifecycle | Partial (vendor hop unknown) | Full | 3-4 -> 5-6 |
| Two material controls | Full (retention open) | Full | |
| Realistic transfer risk | Partial (Unknown) | Full (Yes, with validation named) | |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Row 2, row 3 | Added "Ref E14" to the Azure partnership and zero-retention claims; new evidence row E14 (internal, Org evidence) | X-14, X-17; evidence discipline | Organisational facts are traceable rather than unsupported assertions |
| 2 | Row 2 hop 4 | "prompts and logs kept 12 months" -> "gateway logs kept 12 months" | Internal consistency | Avoids a reader seeing a clash with the provider's zero retention in row 3 |
| 3 | Row 3 control 2 | Added an explicit "Test:" so control 2 matches control 1's structure | Reviewer check "material and testable" | Both controls now pass/fail |
| 4 | Row 4 | "data may cross borders" -> provider "processes prompts and extracts in the EU, outside India" | Rubric "realistic transfer risk" | States the transfer as a fact of the design, not a possibility |
| 5 | Rows 2-4 | Trimmed wording (254 -> 234 words after row 6, including checkbox labels); "organization's" -> "organisation's" | X-16 (proportionate, about 200 words); config UK spelling | Keeps the section within the guide budget |
| 6 | Row 2 hop 4 | Added "held in the organisation's tenant" (learner request 2026-11-10) | Rubric "traceable lifecycle" | Shows the 12-month logs stay under your control, separate from the zero-retention provider copy |
| 7 | Row 3 control 2 | Zero retention "negotiated, Org evidence" -> "Hypothetical: assumed, contract not reviewed for this assignment" (learner decision) | X-17: assumptions labelled, not presented as verified fact | Avoids presenting an unchecked contract term as fact |

## Needs your input
- None. No [CONFIRM] items remain.

## Judgement flags (not changed)
- **Zero retention: resolved as an assumption (learner decision 2026-11-10).** The organisation's contract cannot be reviewed for a course project, so row 3 now labels zero retention as Hypothetical (Ref E14); the Azure partnership and EU region stay Org evidence. Row 4 keeps the contract check as a validation item for a real deployment. Labelling it honestly satisfies X-17 and does not cost marks.
- **Downstream (C3, X-10):** the agent now relies on a bought frontier model. C3 must name Microsoft Azure / the model provider as an external dependency of the "Build" choice. C1 role "provider and deployer (in-house build)" still holds for the system you build, but C3 should state that the general-purpose model's own obligations sit with its provider (VALIDATE).

## Checks
- Arithmetic: none in this section.
- Consistency: X-09 PASS (personal data minimal = C1 India row "only staff names in logs"; cross-border Yes = C1 "Likely yes"; C4 must repeat no-training, zero retention, sub-processors and EU region). X-07 PASS (Strategy & Analytics division lead, Commercial Strategy manager, AI CoE in B2). X-13: C4 90-day objective must include the row 4 validation items. A4 board_uncertainty_2 (data containment) now mapped.
- Evidence: E14 added (internal). E10 used for DPDP Rule 7 (secondary sources, VALIDATE). DPDP transfer-restriction approach per course notes, still VALIDATE.
- Labels: Org evidence on the Azure partnership and EU region, Hypothetical on zero retention, Hypothetical on control 1's test. No [GUIDE] or [CONFIRM] left.

## Next step
- Edit v3 directly if you disagree, then run /prompt-accept C2.
