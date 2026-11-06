---
section: A3
title: "Stage-gated funding and failure controls"
marks: 9
version: v1-template
generated: 2026-11-06T23:30:00+05:30
---
# A3. Stage-gated funding and failure controls (9 marks)

> [GUIDE] Budget: 220 words plus tables. Earns marks: staged capital release, observable gate evidence, a real stop rule, fit between the chosen risk and the mitigation. Full-credit descriptor: 3-4 decision checkpoints, staged resources, actual kill rule, relevant failure-family treatment. Edit the response cells only. Resolve every [CONFIRM]. This is a funding-gate design, not a pilot plan. Your three decisions from chat (kill rule, gate owner, failure family) are already written in.

**Table 1. Decision checkpoints (USD thousands; TCO USD 165k; all thresholds and tranches Hypothetical)**

| Checkpoint / stage(s) | Evidence required for next funding decision | Owner of go / hold / redirect / kill call | Funding / resource release at this stage |
|---|---|---|---|
| 1. Discover / Validate | By end of week 6: HR and Finance agree in writing, in principle, to at least 5 FTE (kill test). Data-access spike covers every approved source; bucket 6 re-estimated at or below USD 90k. Pilot pack 1, on a live monthly request with an analyst validating, takes at most [CONFIRM: 20] analyst-days, every figure from a deterministic query, every claim cited, no data leaving the gateway. Overrides and tokens logged; projected inference at or below USD 20k a year. | Executive sponsor ([CONFIRM: LT role title]) decides; function Finance manager must co-sign any release. Strategy & Analytics division lead presents evidence and has no vote. | USD 25k (15.2% of TCO): spike and source inventory 10, agent workflow and evaluation harness 10, sandbox inference and hosting 3, access design 2. |
| 2. Build | By end of month 3 (day 90): 3 pilot packs average at most [CONFIRM: 20] analyst-days, against the ~15 target. Binding HR and Finance agreement to at least 5 FTE, with reductions starting by month 5. Read-only connectivity live with no write path. Confidentiality and prompt-injection test passed; validation sign-off by a reviewer outside the build team; analysts trained. | Executive sponsor decides; function Finance manager co-signs; [CONFIRM: HR lead title] confirms the headcount evidence. | USD 102k (61.8%): remaining data preparation 50, read-only connectivity 45, security review and tests 5, hosting 2. Released only on a gate 1 pass. |
| 3. Deploy / Monitor | Go-live month 4. Interim review, month 7: hold if live packs average above 20 analyst-days. Scale evidence, end of month 13: packs at or below ~15 analyst-days; no uncited figure reached the LT; escalations logged; function headcount cost down at least USD 20k a month across months 11-13 (Expected USD 40k). | Executive sponsor decides; function Finance manager certifies the budget-line change. | USD 38k (23.0%): inference and hosting 17, monitoring 12, training and escalation 6, validation sign-off and audit support 3. Released only on a gate 2 pass. |
| 4. Scale (conditional) | 90 days of measured headcount saving, traced to the platform rather than the OPEX mandate alone; two quarters of LT decision log; no open critical incident. | LT, on the Executive sponsor's proposal with Finance's written view. | USD 0 of the USD 165k. Any Scale budget is a separate ask, not estimated here and outside the 12-month horizon. |

Releases: 25 + 102 + 38 = 165, equal to the A2.2 total. They include reallocated internal effort of 12, 50 and 21 (83, A2.2 buckets 2-5). If the spike re-estimates bucket 6 above USD 60k, the sponsor must approve the increase; at USD 90k, gate 2 rises to USD 132k and the total reaches the Weak case USD 195k.

**Table 2. Decision controls**

| Decision control | Your response |
|---|---|
| One pre-agreed kill / stop condition: threshold, timing and accountable authority | If HR and Finance have not agreed in writing, in principle, to at least 5 FTE by the end of week 6 (gate 1), the Executive sponsor stops funding. The USD 102k Build tranche is not released and spend stops at about USD 25k; manual packs continue. 5 FTE is half the Expected reduction: USD 20k a month, payback around month 19 before year-2 run costs (165 / 20, from month 11) (Hypothetical, Ref E7). |
| Most material failure-pattern family (misunderstood problem / inadequate data / technology-first / scaling gap / problem difficulty) | Inadequate data. Data preparation is the largest bucket (USD 60k, 36% of TCO), its range runs USD 40-90k, and it is the biggest cost uncertainty in A2.2 (Estimate, Ref E5). Evidence packs are only as reliable as source access, extracts and metadata. |
| One design measure that addresses that failure pattern | Fund data before model: the data-access spike and source inventory run first, inside gate 1. The USD 50k balance of data preparation and all USD 45k of connectivity stay locked until every approved source is confirmed extractable and bucket 6 is re-estimated at or below USD 90k. |

## Why this draft (guide - removed at compile)
> [GUIDE]
> - **Row 1, Discover / Validate** - Basis: small sandboxed release, then the course's Validate test (does it beat the baseline; data, workforce and named owner ready). Justification: observable pass marks, not stakeholder comfort. Uses the live monthly requests as pilot packs because capacity is thin: three extra packs would not fit in six weeks at about 25 analyst-days a month. Sources: knowledge: part-a L3. Consistency: cost_uncertainty, usage_sensitive, baseline_value, ai_boundary. One pack is a thin sample for releasing 62% of the money, which is why row 2 retests on 3 packs before go-live.
> - **Row 2, Build** - Basis: E4 fixes the validation gate before month-4 go-live, so gate 2 sits at day 90 and 9 requests still benefit. Binding agreement is timed so the 6-month reduction runs months 5-10 and the saving starts in month 11, matching A2.1 and A2.3. Sources: knowledge: part-a L3. Consistency: benefit_1_change, headcount_assumptions, downstream_notes.
> - **Row 3, Deploy / Monitor** - Basis: 5 FTE x USD 48k / 12 = USD 20k a month; Expected 10 FTE = USD 40k. The course asks for measurable P&L impact over 90 days before Scale, and the saving only starts in month 11, so this reading falls in month 13, just past the horizon. Costs and scenarios stay on 12 months. Sources: knowledge: part-a L3. Consistency: sc_exp, payback_view, X-01.
> - **Row 4, Scale** - Basis: A2.1 says attribution to the platform is unproven and Scale benefits sit outside the horizon, so no money is shown. The spec allows releases that exclude a conditional Scale, provided that is stated. Consistency: realisation_route, strategic_values, X-11.
> - **Owners** - Basis: the course gives the gate to the executive sponsor, not engineering, and warns that a champion shares the bias. You lead the building division, so you present and do not decide (your choice in chat). Titles must appear in the B2 RACI (X-07).
> - **Release amounts** - Basis: my proposed phasing of the A2.2 lines. Bucket 1: 3 + 2 + 17 = 22. Bucket 2: 10 + 45 = 55. Bucket 3: 2 + 5 + 3 = 10. Bucket 4: 6 in gate 3. Bucket 5: 12 in gate 3. Bucket 6: 10 + 50 = 60. Consistency: tco_total, X-04. A4's tranche must equal the USD 25k gate 1 release or explain the difference.
> - **Kill condition** - Basis: your choice in chat: headcount, end of week 6. The course's kill format is a number, a date and an authority. Every banked benefit depends on this one decision, so it is the earliest test that protects the most money. Consistency: downstream_notes, a4_basis, X-05 (C4 or A4 must cite it).
> - **Failure family and measure** - Basis: your choice in chat. Course prevention is "fund data engineering first"; here that becomes a funding lock, so the measure acts on the named risk. Sources: knowledge: part-a L5. Consistency: tco_b6, cost_uncertainty.
> - **Judgement flag** - The gates limit the downside; they do not fix the case. At the 5 FTE threshold, year-1 benefit is about USD 40k (5 x 48 x 2/12), a net of about (125). Expected stays at (85) and the probability-weighted net at about (74). A4 has to address this directly. Your decision stands; this only flags it.
> - **For later sections** - C4's 90-day objective should span gates 1 and 2 (X-13), since this design splits validation across week 6 and day 90. B2 must include the Executive sponsor, function Finance manager and HR lead.

## To confirm before you save (guide)
> [GUIDE]
> 1. Row 1, pilot pack 1 limit. Recommended default: 20 analyst-days, the Weak case's 5 days saved. Stricter risks stopping on one first pack.
> 2. Row 1, Executive sponsor title. Recommended default: the LT member who most uses the packs; a role title only, no name. Only you know who would take this on.
> 3. Row 2, 3-pack average limit. Recommended default: 20 analyst-days as the hold line, with ~15 remaining the target.
> 4. Row 2, HR lead title. Recommended default: the HR role who can commit support-function reductions.
> 5. Not bracketed, but please check: the release split (25 / 102 / 38), the week-6 timing for HR, and whether Build can finish between week 6 and month 3. If it cannot, go-live moves towards the Weak case's month 7 and E4 and A2.1 must change.
