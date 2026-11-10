---
section: A3
title: "Stage-gated funding and failure controls"
marks: 9
version: final
generated: 2026-11-07T14:00:00+05:30
---
# A3. Stage-gated funding and failure controls (9 marks)

**Table 1. Decision checkpoints (USD thousands; TCO USD 165k; all gates, thresholds and tranches are proposals, Hypothetical, Ref E2, E3)**

| Checkpoint / stage(s) | Evidence required for next funding decision | Owner of go / hold / redirect / kill call | Funding / resource release at this stage |
|---|---|---|---|
| 1. Discover / Validate | By end of week 6: HR and Finance agree in writing, in principle, to at least 5 FTE (kill test). Data-access spike confirms every approved source is extractable; bucket 6 re-estimated at or below USD 90k. Pilot pack 1, on a live monthly request with an analyst validating, takes at most 20 analyst-days, every figure from a deterministic query, every claim cited, no data leaving the gateway. Overrides and tokens logged. | Executive sponsor (Head of Finance, LT member) decides; function Finance manager must co-sign any release. Strategy & Analytics division lead presents evidence and has no vote. | USD 25k (15.2% of TCO): spike and source inventory 10, agent workflow and evaluation harness 10, sandbox inference and hosting 3, access design 2. |
| 2. Build | By end of month 3 (day 90): 3 pilot packs average at most 20 analyst-days, against the ~15 target; projected inference at or below USD 20k a year, otherwise bucket 1 is revisited. Binding HR and Finance agreement to at least 5 FTE, with reductions starting by month 5. Read-only connectivity live with no write path. Confidentiality and prompt-injection test passed. Validation reviewer outside the build team named; analyst training booked. | Executive sponsor decides; function Finance manager co-signs; Head of Business-HR (LT member) confirms the headcount evidence. | USD 102k (61.8%): remaining data preparation 50, read-only connectivity 45, security review and tests 5, hosting 2. Released only on a gate 1 pass. |
| 3. Deploy / Monitor | Go-live month 4, only after that reviewer's validation sign-off and analyst training. Interim review, month 7: hold remaining gate 3 spend if live packs average above 20 analyst-days. Scale evidence, end of month 13 (past the 12-month costing horizon, which is unchanged): packs at or below ~15 analyst-days; no uncited figure reached the LT; escalations logged; function headcount cost down at least USD 20k a month across months 11-13 (Expected USD 40k). | Executive sponsor decides; function Finance manager certifies the budget-line change. | USD 38k (23.0%): inference and hosting 17, monitoring 12, training and escalation 6, validation sign-off and audit support 3. Released only on a gate 2 pass. |
| 4. Scale (conditional) | 90 days of measured headcount saving, traced to the platform rather than the OPEX mandate alone; two quarters of LT decision log; no open critical incident. | LT, on the Executive sponsor's proposal with Finance's written view. | USD 0 of the USD 165k. Any Scale budget is a separate ask, not estimated here and outside the 12-month horizon. |

Releases: 25 + 102 + 38 = 165, equal to the A2.2 total. They include reallocated internal effort of 12, 50 and 21 (83, A2.2 buckets 2-5). If the spike re-estimates bucket 6 above USD 60k, the sponsor must approve the increase; at USD 90k, gate 2 rises to USD 132k and the total reaches the Weak case USD 195k.

**Table 2. Decision controls**

| Decision control | Your response |
|---|---|
| One pre-agreed kill / stop condition: threshold, timing and accountable authority | If HR and Finance have not agreed in writing, in principle, to at least 5 FTE by the end of week 6 (gate 1), the Executive sponsor stops funding. The USD 102k Build tranche is not released and spend stops at about USD 25k; manual packs continue. 5 FTE is half the Expected reduction: USD 20k a month, year-1 benefit USD 40k and net (125), payback around month 19 before year-2 run costs (165 / 20, from month 11) (Hypothetical, Ref E3). |
| Most material failure-pattern family (misunderstood problem / inadequate data / technology-first / scaling gap / problem difficulty) | Inadequate data. Data preparation is the largest bucket (USD 60k, 36% of TCO), its range runs USD 40-90k, and it is the biggest cost uncertainty in A2.2 (Estimate, Ref E2). Evidence packs are only as reliable as source access, extracts and metadata. |
| One design measure that addresses that failure pattern | Fund data before model (proposed control): the data-access spike and source inventory run first, inside gate 1. The balance of data preparation (USD 50k at Expected) and all USD 45k of connectivity stay locked until every approved source is confirmed extractable and bucket 6 is re-estimated at or below USD 90k. |
