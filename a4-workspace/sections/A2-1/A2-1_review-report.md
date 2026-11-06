# Review report - A2.1 Value mechanisms and evidence | 2026-11-06 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Strong and honest: every monetised line shows driver x change x unit value, no payroll saving is assumed, and strategic value stays outside ROI. Held back only by small labelling gaps and an unexplained low-case figure. Seven light edits; no decision changed.

**Rubric position (indicative, not a prediction):**
| Criterion | Before | After | Marks range before -> after (of 5) |
|---|---|---|---|
| A2.1 causal drivers quantified | Full | Full | 4-5 -> 4-5 |
| Actual budget/revenue capture explained | Full (route explicitly "none evidenced", banked USD 0k) | Full | 4-5 -> 4-5 |
| Speculative value kept outside ROI | Full (low case derivation unstated) | Full | 4-5 -> 5 |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Table 1 row 1, Change | "saving ~10 per request" -> "~10 analyst-days per request" | Clarity of unit | Removes ambiguity in the quantified driver |
| 2 | Table 2 row 1 | Turnaround statement labelled (Estimate) and "is targeted to" | Rule 3 / X-17 (no estimate presented as fact) | Avoids the unlabelled-claim deduction |
| 3 | Table 2 row 1 | Low case now "(25% of the best case)" | Transparent workings (E3) | Makes the USD 100-125k figure traceable |
| 4 | Table 2 row 2 | Added "(9 x 10)" to the ~90 days | Arithmetic shown | Ties the figure to Table 1 |
| 5 | Table 1 heading | Added "(USD thousands)" | X-01 | Currency and unit stated once |
| 6 | File | Removed [GUIDE] blocks; all [CONFIRM] items you resolved were kept as written | Compile-ready | Clean text |
| 7 | Evidence log / ledger | E4 marked learner-confirmed; remaining A2.1 ledger keys -> reviewed | a4-ledger | Single source of truth for A2.3 |

## Needs your input
- None. All three [CONFIRM] items were resolved (USD 0k banked; month-4 go-live; total USD 0k).
- Optional: name who owns the LT decision log in Table 2 once B2 roles exist (not invented here).

## Judgement flags (not changed)
- **Expected ROI will be -100% on a USD 0k banked benefit** (net = 0 - A2.2 total). With the Course 2 indicative TCO of USD 90-270k, A2.3 will show a deeply negative Expected case; negative ROI is not penalised, but A4 must reconcile the decision label to it (X-06). A "Go" or "Conditional Go" then rests wholly on strategic value (E3: USD 100-500k, Hypothetical), which the rubric treats as unbanked. A Hold/Conditional Go with a kill threshold in A3 is easier to defend; the choice is yours.
- A2.3 Strong case: monetise more only if a budget line is evidenced; do not pull Table 2 value into it (X-11).

## Checks
- Arithmetic: PASS - 9 x 10 x 0.2 = 18; 12 x 10 x 0.2 = 24; 9 x 10 = 90 days; 25% x 1.6-2M = 400-500k; 25% x 400-500k = 100-125k. (calc_check.py is for A2.2/A2.3; not applicable.)
- Consistency: X-01 PASS; X-11 PASS (nothing strategic in Table 1); X-15 PASS (initiative name and baseline match A1); X-17 PASS after edit 2; X-02 pending A2.2/A2.3 (Expected benefit must be USD 0k banked).
- Evidence: E1, E2, E3 verified in log; E4 confirmed. Length: ~370 words in the tables (no budget stated; acceptable, trim if the 20-page cap tightens).

## Next step
- Edit v3 directly if you disagree, then /prompt-accept A2.1
