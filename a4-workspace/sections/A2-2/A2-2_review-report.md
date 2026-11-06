# Review report - A2.2 Total cost of ownership | 2026-11-06 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** All six buckets are costed with unit logic, labels and a reconciling total of USD 165k; the uncertainty box names a test, quantity and gate. The only rework was the total cell, which had absorbed benefit and net commentary that belongs in A2.1/A2.3. Cost figures are unchanged.

**Rubric position (indicative, not a prediction):**

| Criterion | Before | After | Marks range (of 6) |
|---|---|---|---|
| Six buckets costed or justified as zero | Full | Full | - |
| Total reconciles, no double count | Full | Full | - |
| Uncertainty addressed and testable | Full | Full | 5-6 -> 5-6 |

## Changes made
| # | Where | Change | Rule / basis | Why it helps |
|---|---|---|---|---|
| 1 | Total cell | Removed "Expected benefit USD 80k ... net about (85)"; kept the scope assumption and severance exclusion | Keep cost and benefit separate; single source for net is A2.3 | Avoids a second place where a net figure can drift out of line |
| 2 | Total cell | Scope sentence rewritten as a stated assumption (other functions at no extra cost; platform and workload flat) and "[CONFIRM]" removed | Your answer 2026-11-06 | Clear, labelled assumption instead of an open item |
| 3 | Uncertainty box | Trimmed one word; now about 95 words | 100-word budget | Stays within budget |
| 4 | Front matter | Removed reopened_reason | Compile hygiene | Clean text |

## Needs your input
- None.

## Judgement flags (not changed)
- **Training scope:** bucket 4 trains 4 analysts, while A2.1 claims savings across three functions. A marker may ask who in the other functions is onboarded. Defensible under your "no extra cost" assumption; consider one line if you want it airtight.
- **Half the cost is non-cash:** buckets 2-5 (50%) are reallocated effort, so cash outlay is far lower than USD 165k. Keep the "reallocated, not new cash" wording; it is honest and consistent with A3 tranches later.
- **Severance excluded:** cost-side counterpart of the A2.1 flag; keep it disclosed.

## Checks
- Arithmetic (manual): 8+14=22; 45+10=55; 4+3+3=10; 2.4+3.6=6; 7+5=12; 22+55+10+6+12+60=165; 83/165=50.3%; 60/165=36.4%. PASS, total equals ledger tco_total.
- Consistency: Expected cost 165 matches A2.3; E5, E2, E1 present; no new evidence rows.

## Next step
- Edit v3 directly if you disagree, then /prompt-accept A2.2.
