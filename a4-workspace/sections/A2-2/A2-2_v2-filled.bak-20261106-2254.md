---
section: A2.2
title: "Total cost of ownership (six buckets)"
marks: 6
version: v2-filled
generated: 2026-11-06T20:45:00+05:30
---
# A2.2. Total cost of ownership, six buckets (6 marks)

> [GUIDE] Budget: table cells brief (unit x quantity x period + label); uncertainty box 100 words. Earns marks: all six buckets costed or justified as 0, total reconciles, uncertainty is testable and addresses AI usage cost. Full-credit descriptor: no omitted bucket, no double count, total = sum. Edit only the "12-month estimate" and "Basis / assumptions" columns and the box. Resolve every [CONFIRM].

**Indicative first-12-month costs, Expected case (USD thousands)**

| Cost bucket taught in Course 4 | 12-month estimate (USD k) | Basis / assumptions |
|---|---|---|
| 1. Compute, licences, hosting and AI infrastructure | 32 | Model inference 8 (12 requests, agent live from month 4; routed smaller models for drafting, frontier only for synthesis) (Estimate, Ref E5). Hosting on existing enterprise model gateway, vector store, access controls, logs 14 (Estimate, Ref E5). Subscribed-source access chargebacks 10 (Estimate, Ref E5). [CONFIRM: subscribed-source chargeback is incremental cash, not already in the function budget] |
| 2. Implementation and integration | 55 | Read-only dashboard and source connectivity, no write-back, 45 (Estimate, Ref E5). Agent workflow, prompt templates and evaluation harness build 10 (Hypothetical). Counted here once; pipelines sit in bucket 6. [CONFIRM: build team is internal; state whether this is incremental cash or reallocated effort] |
| 3. Security, privacy, risk and governance | 10 | Access-control design and security review 4; confidentiality and prompt-injection test before go-live 3; validation sign-off and audit support 3 (Hypothetical). Not separately costed in Course 2, so added here. |
| 4. Change management, training and human escalation | 6 | Training and onboarding 4 people x 3 days x USD 0.2k = 2.4 (Estimate, Ref E2). Extra analyst time on escalated or failed packs: 9 requests x 2 days x USD 0.2k = 3.6 (Hypothetical). Reallocated effort, not new cash: routine validation is already inside the ~15 analyst-days per pack (Ref E1). |
| 5. Monitoring, model performance review and maintenance | 12 | Citation and numerical-consistency checks, evidence-gap log, residual-error tracking 7; quarterly drift and prompt/template review 5, for 9 live months (Estimate, Ref E5). |
| 6. Data preparation, cleaning and access enablement | 60 | Approved-source inventory, dashboard extracts, metadata and pipelines (Course 2 range 40-90, lower-mid because dashboards already sit in the enterprise data lake) (Estimate, Ref E5). Largest bucket: 34% of total. [CONFIRM: figure within 40-90 range] |
| **TOTAL first-12-month cost** | **175** | 32 + 55 + 10 + 6 + 12 + 60 = 175. One-off build costs counted once, in the bucket named above. Enterprise platform costs funded elsewhere are excluded (Ref E5). Banked benefit is USD 0k (A2.1), so the Expected case is a net cost of about USD 175k before strategic value. |

**Biggest cost uncertainty and how you would test it (100 words)**

Data preparation (USD 60k, 34% of total). If source extracts or metadata need more work than assumed, it could reach the top of the 40-90k range. Test: a two-week data-access spike before gate 1 inventories every source and extract, and re-estimates the bucket. AI usage cost could change cost only slightly at 12 requests a year, but multi-step agent loops could multiply tokens. Test: run 3 pilot packs, log tokens per pack, and revisit bucket 1 if projected inference exceeds USD 20k a year. Usage-sensitive: yes, driver is tokens per evidence pack (Estimate).

## Why this draft (guide - removed at compile)
> [GUIDE]
- **Bucket 1** - Basis: Course 2 model/inference 5-20k, infrastructure 10-30k, subscribed sources within other recurring 10-30k; lower-mid values because volume is 12 requests. Justification: rubric wants a basis, not a token amount. Sources: knowledge: context-pack worked example; part-a L4, L7. Consistency: E4 (live month 4).
- **Bucket 2** - Basis: Course 2 integration 40-50k, read-only. Justification: shows the largest bucket class and keeps build effort out of bucket 6. Sources: context-pack; part-a L4. Consistency: ai_boundary (read-only).
- **Bucket 3** - Basis: not costed in Course 2; Hypothetical placeholder. Justification: avoids the trap of governance as a token amount; ties to B1-B3 later. Sources: part-a L4.
- **Bucket 4** - Basis: day rate E2 (0.2k), 9 live requests E4. Justification: human escalation is the largest hidden cost in the notes; shown as reallocated effort to avoid double counting with A2.1. Sources: part-a L4.
- **Bucket 5** - Basis: Course 2 monitoring 5-40k, lower end. Justification: monitoring after go-live is a named trap. Sources: context-pack.
- **Bucket 6** - Basis: Course 2 data engineering 40-90k. Justification: data prep is typically undercounted (20-40% of budget in notes); here 34%. Sources: context-pack; part-a L4.
- **Total and box** - Basis: calc_check PASS on 175. Justification: A2.3 Expected cost must equal 175; box names a test, a quantity and a timing. Consistency: tco_total feeds A2.3; A3 gate 1 timing.

## To confirm before you save (guide)
> [GUIDE]
- [CONFIRM] Subscribed-source chargebacks (10) are incremental cash. Default: yes; set to 0 with reason if already budgeted.
- [CONFIRM] Build team is internal and whether bucket 2 is cash or reallocated effort. Default: reallocated effort for staff, cash for contractors; state which.
- [CONFIRM] Bucket 6 figure of 60 within the 40-90 range. Default: 60.
- Optional: adjust bucket 3 (10) and bucket 5 (12) to what your function would actually charge; both are Hypothetical or Estimate.
