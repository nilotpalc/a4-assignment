# Review report - C3 Build vs buy vs partner | 2026-11-10 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Strong. You resolved all 6 [CONFIRM] items (kept Build narrowly, High / Low / Medium, moat Partial, delivery capability as the reversal dependency) and added a sentence that answers the "why Build without a full moat" question directly. What held it back was mechanical: a duplicated sentence pushed the decision table to 209 words against a 180 budget. Edits removed the duplicate, tightened one sentence and corrected two small labels; no decision was changed.

**Rubric position (indicative, not a prediction):**
| Criterion | Before (v2) | After (v3) | Marks range before -> after (of 7) |
|---|---|---|---|
| Three credible options (benefit and constraint specific to the initiative) | Full | Full | 5-6 -> 6-7 |
| Fit-based sourcing tied to A2.2 costs, with compute rationale | Full (over budget, duplicated text) | Full | |
| Explicit, measurable factor that could reverse the choice | Full | Full | |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Decision row 1 | Removed the duplicated "Compute: rent ... could not pay back." sentence | X-16 word budget (209 -> 186 words including the checkbox labels, about 178 without; limit 180, tolerance 198) | Brings the section inside the budget; a repeated sentence reads as carelessness |
| 2 | Decision row 1 | "the binding constraint is data containment (A4), not features ... rests on cost and containment" -> "data containment is the binding constraint (A4) ... rests on containment and cost"; dropped "existing" before Microsoft Azure | Tightening; your added sentence kept in full | Your new sentence carries the argument; the trimmed words repeated it |
| 3 | Decision row 1 | "inference is about USD 8k" -> "first-year inference is about USD 8k" | X-10, accuracy against A2.2 bucket 1 (USD 8k covers the first 12 months with the agent live from month 4) | The figure now matches A2.2 exactly, so a marker cross-checking costs finds no gap |
| 4 | Build row, benefit | "(Ref E5)" -> "(Estimate, Ref E5)" on the USD 55k | X-17 labelling | Estimates are labelled, not presented as fact |
| 5 | Whole file | Removed [GUIDE] blocks for the clean version | Compile rule | None on marks; housekeeping |

| 6 | Decision row 1 | "owned capacity could not pay back" -> "far too little to justify owning hardware" (learner request after review; table now 187 words including checkbox labels) | Clarity; reviewer check "compute ownership/rental rationale present" | The rent rationale is now plain to a non-technical reader |

## Needs your input
- None. No [CONFIRM] items remain.

## Judgement flags (not changed)
- **Build with only a Partial moat.** The course rule is "build in-house only when unique proprietary data creates durable advantage". Your choice is defensible because you scoped it ("Build, narrowly"), named the rented components and stated that it rests on containment and cost, not differentiation. A strict marker could still prefer Partner; the rubric's Low band is "build as prestige", which this is clearly not. Risk to marks: low.
- **"Delivery capability (control risk)".** The label fits (you agreed it is control), but "control" in sourcing usually means ownership of data and workflow. If you have spare words, a clause linking the two would help; not needed for Full.
- **Buy row is untested.** "Hypothetical: no tool assessed" is honest and earns credit for labelling, but the Low rating rests on reasoning, not on an assessment. Acceptable for the assignment.

## Checks
- Arithmetic: none in this section. Figures reused, not recomputed: USD 55k (A2.2 bucket 2), USD 60k (bucket 6), USD 165k (total), USD 8k (inference in bucket 1), USD 102k (A3 gate 2 release), 20 analyst-days (A3 gate 1). All match the ledger.
- Consistency: X-10 PASS (Build matches A2.2 buckets 1-2: internal build team, existing gateway, rented inference; C4 must name Microsoft Azure and the AI CoE gateway as external dependencies and apply the five contract tests to them). X-07 PASS (Executive sponsor, AI CoE exist in B2). X-15 PASS. X-16 PASS (within tolerance). X-17 PASS. C1 eu_ai_act_role unchanged: provider and deployer, because the choice remains an in-house build. X-05/X-13 for C4: the gate 1 switch-to-Partner rule should appear in C4's commercial gate.
- Evidence: no new E-id. E5 (costs), E13 (insider list), E14 (Azure, gateway) reused; C3 added to their "Used in". No legal or regulatory claim made in this section. The unverified course-note statistics on build success rates were deliberately left out.
- Completeness: both tables present with original labels; three option rows; moat box ticked (Partial); compute rent rationale present; reversal dependency tied to gate 1 with a decision owner.

## Next step
- Edit v3 directly if you disagree, then run /prompt-accept C3.
