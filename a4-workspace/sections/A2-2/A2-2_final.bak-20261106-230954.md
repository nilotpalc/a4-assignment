---
section: A2.2
title: "Total cost of ownership (six buckets)"
marks: 6
version: final
generated: 2026-11-06T21:30:00+05:30
---
# A2.2. Total cost of ownership, six buckets (6 marks)

**Indicative first-12-month costs, Expected case (USD thousands)**

| Cost bucket taught in Course 4 | 12-month estimate (USD k) | Basis / assumptions |
|---|---|---|
| 1. Compute, licences, hosting and AI infrastructure | 22 | Model inference 8 (12 requests, agent live from month 4; routed smaller models for drafting, frontier only for synthesis) (Estimate, Ref E5). Hosting on existing enterprise model gateway, vector store, access controls, logs 14 (Estimate, Ref E5). Subscribed-source access chargebacks 0: already in the function budget, so not incremental (Ref E5). |
| 2. Implementation and integration | 55 | Read-only dashboard and source connectivity, no write-back, 45 (Estimate, Ref E5). Agent workflow, prompt templates and evaluation harness build 10 (Hypothetical). Internal build team: reallocated effort, not incremental cash. Counted here once; pipelines sit in bucket 6. |
| 3. Security, privacy, risk and governance | 10 | Access-control design and security review 4; confidentiality and prompt-injection test before go-live 3; validation sign-off and audit support 3 (Hypothetical). Not separately costed in Course 2, so added here. Internal staff: reallocated effort, not incremental cash. |
| 4. Change management, training and human escalation | 6 | Training and onboarding 4 people x 3 days x USD 0.2k = 2.4 (Estimate, Ref E2). Extra analyst time on escalated or failed packs: 9 requests x 2 days x USD 0.2k = 3.6 (Hypothetical). Reallocated effort, not new cash: routine validation is already inside the ~15 analyst-days per pack (Ref E1). |
| 5. Monitoring, model performance review and maintenance | 12 | Citation and numerical-consistency checks, evidence-gap log, residual-error tracking 7; quarterly drift and prompt/template review 5, for 9 live months (Estimate, Ref E5). Internal staff: reallocated effort, not incremental cash. |
| 6. Data preparation, cleaning and access enablement | 60 | Approved-source inventory, dashboard extracts, metadata and pipelines. Within the Course 2 range of 40-90, lower-mid because dashboards already sit in the enterprise data lake (Estimate, Ref E5). Largest bucket: 36% of total. |
| **TOTAL first-12-month cost** | **165** | 22 + 55 + 10 + 6 + 12 + 60 = 165. One-off build costs counted once, in the bucket named above. Buckets 2-5 (83, 50%) are reallocated internal effort. Enterprise platform costs and source subscriptions funded elsewhere are excluded (Ref E5). Banked benefit is USD 0k (A2.1), so the Expected case is a net cost of about USD 165k before strategic value. |

**Biggest cost uncertainty and how you would test it (100 words)**

Data preparation (USD 60k, 36% of total). If source extracts or metadata need more work than assumed, it could reach the top of the 40-90k range. Test: a two-week data-access spike before gate 1 inventories every source and extract and re-estimates the bucket. AI usage could change cost only slightly at 12 requests a year, but multi-step agent loops could multiply tokens. Test: run 3 pilot packs, log tokens per pack, and revisit bucket 1 if projected inference exceeds USD 20k a year. Usage-sensitive: yes; driver is tokens per evidence pack (Estimate).
