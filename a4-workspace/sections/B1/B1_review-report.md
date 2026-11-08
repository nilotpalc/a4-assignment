# Review report - B1 Responsible-AI design obligations | 2026-11-08 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** All four principles are now specific to this agent, owned and testable, and every [CONFIRM] is resolved. Two things held it back: the explainability and transparency tests checked only part of their obligations, and the fairness row ran over budget. Edits tighten the tests so they match the obligations. They add no new facts.

**Rubric position (indicative, not a prediction):**
| Criterion | Before | After | Marks range before -> after (of 7) |
|---|---|---|---|
| Four principles become testable obligations | Full (lower): three rows tight; explainability/transparency proof partial | Full | 5-6 -> 6-7 (Estimate) |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Accountability test | "Quarterly audit" -> "Validation reviewer's quarterly audit" | Reviewer check: test must be owned; role already in A3 gates | An audit with a named owner can be run, so the proof is not weak |
| 2 | Transparency test | "100% allowlisted" -> "label present and 100% of claims trace to an allowlisted source" | Full descriptor: test proves the whole obligation | The label was promised but never checked; now both parts are tested |
| 3 | Explainability | Obligation trimmed 27 -> 22 words; test adds "checks all four fields" and "any gap or mismatch" | Test must match obligation; X-16 budget | Before, the test only reproduced figures. Now it also checks the contrary-evidence, confidence and gaps fields |
| 4 | Fairness obligation | "Evidence quality" -> "Citation accuracy"; China clause shortened | Measurable wording; X-12 (B3 uses same metric) | The obligation now names the metric the test measures |
| 5 | Fairness test | "by sector and region, anonymised" -> "The 20 quarterly claims span every sector and region"; "only" dropped | Reviewer check: test can be run; X-16 | Ties the test to your sample of 20. Row is 57 words, inside the +10% tolerance |
| 6 | Whole file | [GUIDE] blocks removed; version v3-reviewed | Edit rules | Clean text ready to accept |

## Needs your input
- No [CONFIRM] items remain.
- Optional: the sector and region names together could help identify the organisation. Recommended: keep them, because each one is generic. If you want more caution, change them to "three business sectors" and "four regions".

## Judgement flags (not changed)
- **Fairness sample size:** 20 claims spread over 3 sectors and 4 regions gives about 5-7 claims per group. One wrong citation then moves a group by 14-20 points, so a single error trips the 10-point pause. "Indicative" is honest, but a marker may see the threshold as noise. You could pool a rolling four quarters (80 claims) or raise the quarterly sample. The 20 claims and 10 points are your numbers and stay as written.
- **Independence (carried from template):** the Executive sponsor owns outcomes and leads the function whose Finance team confirmed USD 48k per FTE. B2 must place the validation reviewer outside that reporting line.
- **Headcount (carried):** the fairness row closes the route to role selection. B3 must still address workforce impact and risk tier.

## Checks
- Arithmetic: not applicable (no sums). Word counts: 50 / 47 / 48 / 57 (budget 28-52, +10% tolerance) PASS.
- Consistency: X-07/X-12: Executive sponsor and validation reviewer are A3 roles, so B2 must carry both with one Accountable. B3 must use citation accuracy by sector and region with the same 10-point gap. X-15 initiative name matches. X-17 Hypothetical label kept. ledger ob_fairness updated (sector/region, China excluded).
- Evidence: E8 cited and present. NIST AI RMF confirmed by the learner from their own research; NIST says a revision is in progress, so re-check before submission. No E-ids added.

## Next step
- Edit v3 directly if you disagree, then /prompt-accept B1
