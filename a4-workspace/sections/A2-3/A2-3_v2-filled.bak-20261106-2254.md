---
section: A2.3
title: "Weak / expected / strong cases"
marks: 7
version: v2-filled
generated: 2026-11-06T21:50:00+05:30
---
# A2.3. Weak / expected / strong value cases (7 marks)

> [GUIDE] Budget: about 180 words after the numbers. Earns marks: three coherent cases, probabilities total 100, transparent arithmetic, sober interpretation. Full-credit descriptor: weak case genuinely weak, Expected cost = A2.2 total (165), payback wording matches the numbers. Negative ROI is acceptable; do not make the case profitable. UPDATED 2026-11-06: the Strong case is now positive on the learner's headcount rationale, so it must stay clearly labelled Hypothetical and be the minority (25%) case. Edit the table values and the Questions table. Resolve every [CONFIRM].

**12-month cases (USD thousands). Net benefit = measurable benefits - total costs; Simple ROI = net / costs x 100. Losses in brackets.**

| Scenario | Likelihood (%) | 12-month measurable benefits | 12-month total costs | Net benefit / (loss) | Simple ROI (%) |
|---|---|---|---|---|---|
| Weak | 25 | 0 | 195 | (195) | -100.0 |
| Expected | 50 | 0 | 165 | (165) | -100.0 |
| Strong | 25 | 240 | 170 | 70 | 41.2 |

Workings. Expected: benefit USD 0k banked (A2.1); cost USD 165k (A2.2 total). Weak: live month 7, 6 requests x 5 days x USD 0.2k = USD 6k capacity, none banked; cost 165 + 30 (data preparation at the top of its range, 90 instead of 60) = 195 (Hypothetical). Strong (Hypothetical, learner rationale 2026-11-06): live month 3; the benefit mechanic is headcount reduction, not banked capacity. Strong data quality supports high-quality answers across leadership dilemmas, so the ~50-member strategy function (Commercial Strategy, Finance, Business Strategy teams often work the same problem) could fall to ~30, refocused on synthesis rather than analysis: 20 FTE x USD 48k = USD 960k annualised (USD 48k per resource is consistent with E2: USD 0.2k/day x ~240 days). Savings take 6 months to realise after the 3-month go-live, so about 3 of the 12 months fall in year 1: 960 x 3/12 = USD 240k. Cost 165 + 5 (extra inference from iteration) = 170. Net 240 - 170 = 70; ROI 70 / 170 = 41.2%. The earlier mechanic (10 requests x 12 days x USD 0.2k = USD 24k capacity, half banked = USD 12k) is superseded in the Strong case and is not added, to avoid double counting. Probability-weighted net: 0.25 x (195) + 0.5 x (165) + 0.25 x 70 = (113.75), about (114). Strategic value (USD 100-125k to 400-500k a year, Ref E3) is excluded from every case. Severance or transition costs are not included in the Strong cost [CONFIRM: add, or state excluded].

| Question | Your response |
|---|---|
| 1. What explains the movement from Weak to Strong? | Five drivers (Hypothetical, Ref E6): go-live month (7, 4, 3), days saved per request (5, 10, 12), realised benefit route (none, none, headcount reduction of 20 FTE, USD 960k annualised, 3 months realised = USD 240k), data-preparation cost (90, 60, 60) and inference cost (8, 8, 13). Weak and Expected stay at USD 0k banked because saved days are reallocated effort, not cash; only the Strong case assumes a structural reduction in the strategy function. The Strong benefit rests on a decision outside this initiative and is not evidenced by A2.1. [CONFIRM: 20 FTE reduction and HR/Finance agreement] |
| 2. Indicative payback expectation, or why payback is not reached in 12 months | Not reached in Weak or Expected. Capacity value alone (USD 24k a year at run-rate) needs about 6.9 years to recover USD 165k; the strategic low case (USD 100-125k a year, Hypothetical, Ref E3) would shorten it to about 1.3-1.7 years. Strong (25% likely) recovers its cost within the year on the 12-month totals (240 vs 170): headcount savings of about USD 80k a month start after month 9, so USD 170k is recovered about 2.1 months into realisation, around month 12 if costs are mostly spent by then (Hypothetical; cost phasing not modelled). |
| 3. What evidence would most improve confidence in your financial case? | HR and Finance confirmation that a headcount reduction is possible and when (Ref E6); the bucket 6 data-access spike before gate 1; analyst-days and tokens timed on the first 3 pilot packs; a Finance ruling on whether released capacity cuts any budget line; a decision log linking LT answers to later opportunity outcomes (Ref E3). |

## Why this draft (guide - removed at compile)
> [GUIDE]
- **Likelihoods** - Basis: learner agreed 25/50/25 (2026-11-06). Justification: the weak tail is as likely as the strong one because data readiness is Medium and Talent is Low (context pack). Consistency: scenario_probabilities.
- **Expected row** - Basis: A2.1 banked USD 0k, A2.2 total 165. Justification: rule says use A2.1 and A2.2 totals; negative ROI is not penalised, an invented profit would be. Consistency: measurable_benefits_total_expected, tco_total.
- **Weak row** - Basis: delay (month 7) and bucket 6 at the top of the 40-90 range plus the A2.2 uncertainty box. Justification: genuinely weak (not 10% lower): later go-live, smaller saving, higher cost.
- **Strong row** - Basis: month 3 go-live, 12 days saved, learner rationale on headcount (replaces the half-capacity-banked mechanic). Justification: shows what must be true for any hard benefit: a headcount reduction of 20 FTE (USD 960k annualised, 3 of 12 months = USD 240k). Now positive (ROI 41.2%), so it is kept Hypothetical, 25% likely and flagged for Finance/HR agreement; the probability-weighted net remains negative. Cost rises with usage to avoid the "cost constant while benefits grow" trap.
- **Question 1** - Basis: five named drivers with a value per scenario. Question 2 - Basis: calc 165/24 = 6.9 years; 165/125 = 1.3, 165/100 = 1.7 years. Question 3 - Basis: A2.2 uncertainty tests, A2.1 decision log.
- **Sources** - knowledge: part-a L4 (three scenarios), L6 (two-column rule, lead with the smaller number); earlier work: context-pack I-1.
- **Arithmetic** - calc_check: all PASS; probability-weighted net (113.75), recomputed 2026-11-06 with Strong 240 / 170 / 70 / 41.2%.

## To confirm before you save (guide)
> [GUIDE]
- RESOLVED: Likelihoods 25 / 50 / 25 agreed.
- RESOLVED (rationale recorded, 2026-11-06): the learner accepted a Strong-case benefit via headcount reduction (50 to 30, 20 x USD 48k = USD 960k annualised, 3 months realised = USD 240k). This replaces the 50%-of-capacity-banked mechanic in Strong only.
- Open [CONFIRM] (a) Reconcile with A2.1: A2.1 capacity is only 300 analyst-days a year (about 1.25 FTE at ~240 days), so a 20 FTE reduction is far larger than this initiative's workload. State it as a wider strategy-function effect, or reduce it.
- Open [CONFIRM] (b) Sober guidance: Strong is now positive; keep it labelled Hypothetical and the minority case. Timing: go-live month 3 + 6 months means benefit starts from month 10, so 3 months (10-12) fits; if it starts at month 9 it is 4 months (USD 320k).
- Open [CONFIRM] (c) Severance, redundancy, transition and knowledge-loss costs are not in the Strong cost (170).
- Open [CONFIRM] (d) HR and Finance agreement; the headcount figures (50, 30, USD 48k) may need a new E-id (E7 proposed, Org evidence if verified).
- Open (e) A4 note changed: not all three ROIs are negative. Weak and Expected are -100%; Strong is +41.2%; probability-weighted net (113.75) is still negative. The A4 ask (small gated tranche, stop rule) must rest on strategic value and the Strong upside being unproven, not on "all ROIs negative".
