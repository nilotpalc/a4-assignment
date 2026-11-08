# Review report - B3 Ethics review, fairness, human oversight | 2026-11-08 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** All four controls are specific and testable. The draft names the error that hurts most and gives its metric a threshold, a cadence and stated limits, and the human has evidence, time and authority. Two gaps held it back: the oversight row had no training and no check on the approver, and the re-review and blocker rows did not say who acts. Edits closed both gaps. One structural issue remains: on a 20-claim sample, the 10-point gap test overrides the 95% threshold (see Judgement flags).

**Rubric position (indicative, not a prediction):**
| Criterion | Before | After | Marks range before -> after (of 8) |
|---|---|---|---|
| Correct review triggers | Full: pre-deployment and material change, both observable | Full: re-review owner named | |
| Fit-for-purpose outcome quality / fairness | Full (lower): metric fits the error; limits stated | Full (lower): unchanged, see flag | |
| Meaningful human authority | Partial-Full: evidence, time and override present; no training; nothing tests the approval | Full: trained approver; quarterly sample re-checks approved packs | |
| Overall | | | 6-7 -> 7 (Estimate) |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Row 1, trigger 2 | "sends the agent back for re-review within 2 working days" -> the validation reviewer re-runs the affected B1 tests within 2 working days | Reviewer check: triggers observable, owner explicit; X-07 | Shows who acts and what is re-tested, not just that a review happens |
| 2 | Row 2 | "Accuracy gap" -> "Supported-claim gap" | Consistency of terms | One metric name throughout, so the gap is clearly the same measure split by sector and region |
| 3 | Row 3 | Added: the manager is trained before go-live (A3 gate 3 books the training) | L6: oversight needs a trained human | Adds the missing fourth condition for meaningful oversight (equipped, trained, authorised, given time) |
| 4 | Row 3 | Added: the quarterly sample re-checks approved packs, so approval is tested, not assumed | Reviewer check: mitigation for automation bias (sampling) | Answers the "rubber stamp" objection with an existing control, at no extra cost |
| 5 | Row 4 | Added: the validation reviewer pauses releases (B2) | X-07; B2 launch_blocker | Ties the blocker to a named authority in B2 |
| 6 | Whole file | [GUIDE] blocks removed; "before LT release" dropped from row 3 time (already stated); version v3-reviewed | Edit rules; budget | Clean text ready to accept |

## Needs your input
- No [CONFIRM] items remain. You confirmed 95% and at least 1 working day at the defaults, and you left out the optional third automation-bias control. That choice is fine now that change 4 covers sampling.

## Judgement flags (not changed)
- **The gap test overrides the 95% threshold.** 20 claims split across 3 sectors gives about 7 claims per sector, and across 4 regions about 5 per region. One unsupported claim drops its sector to about 86% (a gap of about 14 points) and its region to 80% (a gap of 20 points), while the others stay at 100%. Either gap breaches the 10-point limit and pauses release. In practice the one miss that 95% allows still blocks release, so the rule works like a 100% threshold. A marker may call the pairing internally inconsistent. You accepted the small-sample flag in B1, and both numbers are your decisions. If you want them to fit, the smallest change is to judge the gap on pooled samples, for example the last 4 quarters (80 claims), and keep 95% per sample. That would change B1's fairness row and need a B1 reopen. Otherwise leave both as they are and say in the limits that the gap test works as a strict, conservative trigger.
- **Length:** about 272 words, about 5% over the 260 budget and inside the 10% tolerance (286). Do not add more.

## Checks
- Arithmetic: 1 miss in 20 = 95% (consistent). One miss in about 7 = about 86%; one miss in 5 = 80% (see the flag above).
- Consistency: X-07 PASS (validation reviewer, AI CoE Project Lead, Commercial Strategy manager, LT all exist in B2; analysts are the ledger's users). X-12 PASS (row 3 evidence matches B1's explainability fields; the metric reuses B1's 20-claim sample and 10-point gap). Gate 3 PASS (go-live month 4 after independent validation and training). X-17 PASS (Hypothetical label on the table).
- Evidence: no legal or external claims; no E-ids added or needed.

## Learner decision 2026-11-08
- Gap-vs-threshold flag: keep both numbers and note it in the limits (B1 not reopened). Row 2 limits now read: "with 20 claims, one miss can breach the gap, so the gap test is deliberately strict and indicative only." The pairing is now declared as a deliberate choice, which answers the inconsistency objection. The band is unchanged (estimate about 7 of 8).

## Next step
- Edit v3 directly if you disagree, then /prompt-accept B3
