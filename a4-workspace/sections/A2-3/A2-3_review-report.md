# Review report - A2.3 Weak / expected / strong cases | 2026-11-06 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Three coherent cases, probabilities total 100, arithmetic passes calc_check, and Expected is back to a sober loss (net (85), ROI -51.5%). Cost and benefit tie to the accepted A2.2 (165) and A2.1 (80). Edits were limited to tightening the three answers toward the word budget and removing guide text.

**Rubric position (indicative, not a prediction):**

| Criterion | Before | After | Marks range (of 7) |
|---|---|---|---|
| Three coherent cases, Weak genuinely weak | Full | Full | - |
| Probabilities 100, transparent arithmetic | Full | Full | - |
| Sober interpretation, payback matches numbers | Full | Full | 5-7 -> 5-7 |

## Changes made
| # | Where | Change | Rule / basis | Why it helps |
|---|---|---|---|---|
| 1 | Q1 | Cut to about 50 words (cut again at your request); drivers in one line; attribution doubt and (165) sensitivity kept | ~180-word budget | Keeps the marked content, cuts repetition |
| 2 | Q2 | Shortened; Strong payback now "late in month 12" (cumulative benefit 240 exceeds cost 170 only after month 12 starts to accrue) | Payback wording must match numbers | Avoids implying early payback |
| 3 | Q3 | Condensed to a list of evidence items | Budget | Same content, fewer words |
| 4 | Front matter and guide | Removed guide blocks and resolved items | Compile hygiene | Clean text |

## Needs your input
- None blocking.

## Judgement flags (not changed)
- **Word budget:** resolved at your request: Q1 and Q3 cut further, the three answers now total about 150 words (budget about 180). The workings paragraph above is required and unchanged.
- **Strong is positive only through the headcount decision:** 20 FTE is a Hypothetical assumption and the 3-month timing is aggressive against a 6-month transition. Label and sensitivity are kept; do not let A4 lean on Strong.
- **Probability-weighted net is (74):** A4 must be sober against this, not against the Strong case.
- **Severance excluded** from Strong and Expected costs; keep disclosed.

## Checks
- Arithmetic (calc_check.py, a4-workspace/.state/calc_alt_A.json): all PASS - buckets 165; Weak 0/195/(195)/-100.0; Expected 80/165/(85)/-51.5; Strong 240/170/70/41.2; probabilities 100; Expected cost = A2.2 total; EV (73.75). Payback by hand: 165/40 = 4.1; 170/80 = 2.1; 165/24 = 6.9 years.
- Consistency: Expected benefit 80 = A2.1 total; ledger sc_* and ev_net match; E6 and E7 reflect 2/12 and 3/12.

## Next step
- Edit v3 directly if you disagree, then /prompt-accept A2.3.
