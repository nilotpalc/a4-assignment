# Review report - C1 Regulatory applicability map | 2026-11-10 (second review, after reopen) | v2-filled -> v3-reviewed

**Verdict in 3 lines:** v2 was unchanged since the reopen, and you asked for a fresh review anyway. The map was already close to Full. This pass made it more precise: row 2 now states that the EU AI Act likely applies, based on your own facts, instead of hedging. One unverified date that does not bear on this initiative was dropped, and the VALIDATE tags now use the same form throughout. The table is 242 words, exactly at the limit.

**Rubric position (indicative, not a prediction):**
| Criterion | Before | After | Marks range before -> after (of 8) |
|---|---|---|---|
| Relevant regimes only, with status and resulting controls | Full if VALIDATE items are cleared; row 2 applicability hedged | Full if VALIDATE items are cleared; applicability stated precisely | 6-7 -> 6-7 (Estimate; firmer within the band) |

## Changes made (previous report archived in the log, superseded)
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Row 2, applicability | "Possibly - validate" -> "Likely yes, limited (VALIDATE): EU and US LT members use the packs, so outputs are used in the EU" | Course notes: reach follows where output is used; Full descriptor: applicability with reasons | You confirmed EU-based users, so "possibly" understated it. A clear applicability call with limited duties reads as analysis, not hedging. |
| 2 | Row 1, obligation | Removed "consent managers from 14 November 2026 (VALIDATE)"; the 18-month date is now tagged "VALIDATE exact date" | Relevance; budget; the date is not verified on PIB | No consent processing happens in this design, so the date added an unverified claim with no design consequence. |
| 3 | Rows 1 and 3 | "(validate)" -> "(VALIDATE)"; "CERT-In clock (B4)" -> "CERT-In clock" | Consistent markers for compile lint; budget | Every open legal item is now easy to find before submission. |

## Needs your input
- None. No [CONFIRM] items remain.

## Judgement flags (not changed)
- The "Likely yes" call on the EU AI Act is an applicability view, not a legal opinion. Keep the VALIDATE tag and make sure legal counsel confirms it. If counsel says EU-based LT use does not count as an EU-located deployer, change it back to "Possibly".

## Checks
- Arithmetic: not applicable.
- Consistency: X-08 PASS (B4 Tier 1, not high-risk). X-09 and X-10 are pending C2/C3 (no personal data by design; provider role assumes Build). X-14 PASS: E9-E13 exist. X-16 PASS at 242 words (limit 242). X-17 PASS: Org evidence label present, and unverified dates are tagged VALIDATE.
- Evidence: unchanged. E10 is partly verified on PIB, the consent-manager date is no longer used, and E11/E12 are still VALIDATE (official sites blocked automated access).

## Next step
- If you disagree with anything, edit v3 directly, then run /prompt-accept C1.
