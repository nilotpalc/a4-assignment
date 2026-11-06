---
section: A2.3
title: "Weak / expected / strong cases"
marks: 7
version: v1-template
generated: 2026-11-06T21:50:00+05:30
---
# A2.3. Weak / expected / strong value cases (7 marks)

> [GUIDE] Budget: about 180 words after the numbers. Earns marks: three coherent cases, probabilities total 100, transparent arithmetic, sober interpretation. Full-credit descriptor: weak case genuinely weak, Expected cost = A2.2 total (165), payback wording matches the numbers. Negative ROI is acceptable; do not make the case profitable. Edit the table values and the Questions table. Resolve every [CONFIRM].

**12-month cases (USD thousands). Net benefit = measurable benefits - total costs; Simple ROI = net / costs x 100. Losses in brackets.**

| Scenario | Likelihood (%) | 12-month measurable benefits | 12-month total costs | Net benefit / (loss) | Simple ROI (%) |
|---|---|---|---|---|---|
| Weak | 25 [CONFIRM: your judgement of likelihood] | 0 | 195 | (195) | -100.0 |
| Expected | 50 | 0 | 165 | (165) | -100.0 |
| Strong | 25 | 12 | 170 | (158) | -92.9 |

Workings. Expected: benefit USD 0k banked (A2.1); cost USD 165k (A2.2 total). Weak: live month 7, 6 requests x 5 days x USD 0.2k = USD 6k capacity, none banked; cost 165 + 30 (data preparation at the top of its range, 90 instead of 60) = 195 (Hypothetical). Strong: live month 3, 10 requests x 12 days x USD 0.2k = USD 24k capacity, half banked = USD 12k (Hypothetical); cost 165 + 5 (extra inference from iteration) = 170 (Hypothetical). Probability-weighted net: 0.25 x (195) + 0.5 x (165) + 0.25 x (158) = (170.75), about (171). Strategic value (USD 100-125k to 400-500k a year, Ref E3) is excluded from every case.

| Question | Your response |
|---|---|
| 1. What explains the movement from Weak to Strong? | Five drivers (Hypothetical, Ref E6): go-live month (7, 4, 3), days saved per request (5, 10, 12), share of released capacity that changes a budget line (0%, 0%, 50%), data-preparation cost (90, 60, 60) and inference cost (8, 8, 13). Even Strong loses money on measurable value, because saved days are reallocated effort, not cash. [CONFIRM: 50% banked in Strong is your assumption, with Finance agreement] |
| 2. Indicative payback expectation, or why payback is not reached in 12 months | Not reached in any case. Capacity value alone (USD 24k a year at run-rate) needs about 6.9 years to recover USD 165k. Only unproven strategic value could shorten it: about 1.3-1.7 years at the USD 100-125k low case (Hypothetical, Ref E3). |
| 3. What evidence would most improve confidence in your financial case? | The bucket 6 data-access spike before gate 1; analyst-days and tokens timed on the first 3 pilot packs; a Finance ruling on whether released capacity cuts any budget line; a decision log linking LT answers to later opportunity outcomes (Ref E3). |

## Why this draft (guide - removed at compile)
> [GUIDE]
- **Likelihoods** - Basis: provisional ledger 25/50/25. Justification: placeholder for your judgement; the weak tail is as likely as the strong one because data readiness is Medium and Talent is Low (context pack). Consistency: scenario_probabilities.
- **Expected row** - Basis: A2.1 banked USD 0k, A2.2 total 165. Justification: rule says use A2.1 and A2.2 totals; negative ROI is not penalised, an invented profit would be. Consistency: measurable_benefits_total_expected, tco_total.
- **Weak row** - Basis: delay (month 7) and bucket 6 at the top of the 40-90 range plus the A2.2 uncertainty box. Justification: genuinely weak (not 10% lower): later go-live, smaller saving, higher cost.
- **Strong row** - Basis: month 3 go-live, 12 days saved, half the capacity banked. Justification: shows what must be true for any hard benefit, and stays negative to keep the case sober. Cost rises with usage to avoid the "cost constant while benefits grow" trap.
- **Question 1** - Basis: five named drivers with a value per scenario. Question 2 - Basis: calc 165/24 = 6.9 years; 165/125 = 1.3, 165/100 = 1.7 years. Question 3 - Basis: A2.2 uncertainty tests, A2.1 decision log.
- **Sources** - knowledge: part-a L4 (three scenarios), L6 (two-column rule, lead with the smaller number); earlier work: context-pack I-1.
- **Arithmetic** - calc_check: all PASS; probability-weighted net (170.75).

## To confirm before you save (guide)
> [GUIDE]
- [CONFIRM] Likelihoods 25 / 50 / 25 (must total 100). Default: keep.
- [CONFIRM] 50% of released capacity banked in the Strong case (needs Finance agreement). Default: keep as Hypothetical, or set 0 to keep all cases at USD 0k.
- Note for A4: all three ROIs are negative on measurable value. The ask must be a small, gated first tranche justified by strategic value and a stop rule.
