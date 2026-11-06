---
section: A2.3
title: "Weak / expected / strong cases"
marks: 7
version: v2-filled
generated: 2026-11-06T23:05:00+05:30
---
# A2.3. Weak / expected / strong value cases (7 marks)

> [GUIDE] Budget: about 180 words after the numbers. Earns marks: three coherent cases, probabilities total 100, transparent arithmetic, sober interpretation. Full-credit descriptor: weak case genuinely weak, Expected cost = A2.2 total (165), payback wording matches the numbers. Negative ROI is acceptable; do not make the case profitable. UPDATED 2026-11-06 (learner feedback): Expected is negative again (2/12 months of headcount benefit); Strong is the only positive case and stays Hypothetical. Edit the table values and the Questions table.

**12-month cases (USD thousands). Net benefit = measurable benefits - total costs; Simple ROI = net / costs x 100. Losses in brackets.**

| Scenario | Likelihood (%) | 12-month measurable benefits | 12-month total costs | Net benefit / (loss) | Simple ROI (%) |
|---|---|---|---|---|---|
| Weak | 25 | 0 | 195 | (195) | -100.0 |
| Expected | 50 | 80 | 165 | (85) | -51.5 |
| Strong | 25 | 240 | 170 | 70 | 41.2 |

Workings. Expected (Hypothetical, Ref E7): live month 4 and a 6-month reduction timeline, so the headcount saving starts in month 11 and 2 of 12 months count: 10 FTE x USD 48k x 2/12 = USD 80k (A2.1 benefit 2; A2.1 capacity value USD 18k is not added). Cost USD 165k (A2.2 total). Net 80 - 165 = (85); ROI (85) / 165 = -51.5%. Weak: live month 7, 6 requests x 5 days x USD 0.2k = USD 6k capacity, none banked; headcount reduction not realised within the year, so benefit 0; cost 165 + 30 (data preparation at the top of its range, 90 instead of 60) = 195 (Hypothetical). Strong (Hypothetical, Ref E7): live month 3, benefit from month 10, so 3 of 12 months count: 20 FTE x USD 48k x 3/12 = USD 240k (USD 960k annualised); cost 165 + 5 (extra inference from iteration) = 170. Net 240 - 170 = 70; ROI 70 / 170 = 41.2%. FTE counts are assumptions for this assignment; only USD 48k per FTE is Finance-confirmed (Org evidence). Severance, redundancy and transition costs are excluded as wider-organisation restructuring, out of scope. Probability-weighted net: 0.25 x (195) + 0.5 x (85) + 0.25 x 70 = (73.75), about (74). Strategic value (USD 100-125k to 400-500k a year, Ref E3) is excluded from every case.

| Question | Your response |
|---|---|
| 1. What explains the movement from Weak to Strong? | Five drivers (Hypothetical, Ref E6, E7): go-live month (7, 4, 3), days saved per request (5, 10, 12), headcount reduction (none; 10 FTE for 2 of 12 months = USD 80k; 20 FTE for 3 of 12 months = USD 240k), data-preparation cost (90, 60, 60) and inference cost (8, 8, 13). Saved analyst days alone bank nothing; any measurable benefit depends on a headcount decision outside this initiative, driven by the organisation's 50% OPEX cut over 5 years. The FTE counts are assumptions for this assignment, not agreed with HR or Finance, and the cut might happen under the mandate anyway, so attribution to the platform is not proven. Sensitivity: if the reduction is not realised, Expected falls to a net of (165) and ROI -100%. |
| 2. Indicative payback expectation, or why payback is not reached in 12 months | Weak: not reached. Expected (Hypothetical): savings of about USD 40k a month (10 x 48 / 12) once the reduction is complete recover USD 165k after about 4.1 months of realisation; with the saving starting in month 11, payback is not reached in the 12 months (only USD 80k is recovered) and falls around month 15 (cost phasing not modelled). Strong (25% likely): about USD 80k a month recovers USD 170k after about 2.1 months, around month 12. Without the headcount decision, capacity value alone (USD 24k a year) needs about 6.9 years. |
| 3. What evidence would most improve confidence in your financial case? | HR and Finance confirmation of the number and timing of headcount reductions and that the benefit is attributable to the platform, not the OPEX programme alone (Ref E7); the bucket 6 data-access spike before gate 1; analyst-days and tokens timed on the first 3 pilot packs; a Finance ruling on whether released capacity cuts any budget line; a decision log linking LT answers to later opportunity outcomes (Ref E3). |

## Why this draft (guide - removed at compile)
> [GUIDE]
- **Likelihoods** - learner agreed 25/50/25 (2026-11-06). Consistency: scenario_probabilities.
- **Expected row** - Learner feedback 2026-11-06: Expected gets 2 of 12 months (go-live month 4 + 6-month transition = benefit from month 11), so benefit 80, cost = A2.2 total 165, net (85), ROI -51.5%. Back to negative, which fits the rubric's "do not make the case profitable" and the attribution doubt.
- **Weak row** - delay (month 7), bucket 6 at 90, headcount benefit 0 (learner-confirmed). Genuinely weak.
- **Strong row** - unchanged 240 / 170 / 70 / 41.2%; Hypothetical; 3 months, so Expected (2) no longer exceeds Strong.
- **Probability-weighted net** - (73.75); calc_check PASS (a4-workspace/.state/calc_alt_A.json, same figures).
- **Judgement flag** - Strong is positive only through an unagreed headcount decision; keep the Hypothetical label and the sensitivity line.
- **Other functions' access** - no extra cost (learner-confirmed): platform and strategy workload stay flat as duplicated project work falls. Consistent with A2.2.

## To confirm before you save (guide)
> [GUIDE]
- RESOLVED (learner, 2026-11-06): timing Expected 2/12, Strong 3/12; Weak headcount 0; Expected negative; FTE counts Hypothetical (assumed for the assignment); no extra cost for other functions; severance excluded.
- A4 basis: probability-weighted measurable net is negative (about -74); the only positive case (Strong) rests on an unagreed headcount decision; strategic value is unproven.
