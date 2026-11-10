---
section: C3
title: "Build vs buy vs partner"
marks: 7
version: final
generated: 2026-11-10T19:30:00+05:30
---
# C3. Build vs Buy vs Partner decision (7 marks)

**Comparison of the three paths**

| Option | One benefit for this initiative | Most important constraint / risk | Fit: High / Medium / Low |
|---|---|---|---|
| Build in-house | Confidential dashboards, prompts and packs stay inside the organisation's tenant (A4, C2). The workflow layer is built by the internal team on the existing AI CoE model gateway: USD 55k of reallocated effort in A2.2 bucket 2, not new cash (Estimate, Ref E2). | Small delivery team (2-3 part-time analysts, Org evidence, Course 3) for the data-engineering load, the largest cost in A2.2 (USD 60k); the evaluation routine lapses if the owner moves. | High |
| Buy existing tool / service | Fastest start; the vendor carries maintenance and model upgrades (Hypothetical: no tool assessed). | Unpublished price-sensitive results (Ref E6) would be processed in a vendor's service, where entitlement-scoped access and the source allowlist (C2 control 1) may not be enforceable. Licence would be new cash, not quoted (VALIDATE). | Low |
| Partner / integrate with specialist | Adds data-engineering and evaluation-harness capacity and could shorten the path to gate 2 (Hypothetical). | Partner staff would need access to unpublished results, so insider-list registration (Ref E6); fees are new cash on top of the USD 165k; know-how may leave with the partner. | Medium |

**Decision**

| Decision | Your response |
|---|---|
| 1. Recommended approach and why | Build, narrowly. The organisation builds only the agent workflow, source connectors and evaluation harness, and rents frontier models through the Microsoft Azure partnership and AI CoE model gateway (Ref E6). Highest fit: data containment is the binding constraint (A4), and the build uses reallocated effort (A2.2). The choice rests on containment and cost, not differentiation; the moat is only partial (row 2). Compute: rent. At 12 requests a year, first-year inference is about USD 8k (Estimate, Ref E2), far too little to justify owning hardware. |
| 2. Does a real proprietary data moat justify a custom build? [ ] Yes [ ] Partial [ ] No - explain | [ ] Yes [x] Partial [ ] No. The proprietary asset is over a decade of sales history in internal dashboards (Org evidence): unique and durable, but the agent only reads it. No model is trained on it, so the agent itself has no moat. The data justifies in-house containment, not a custom model. |
| 3. One dependency that could reverse the decision (economics, control, data, integration or vendor risk) | Delivery capability (control risk). If pilot pack 1 at gate 1 (end week 6) takes more than 20 analyst-days, or fails its citation or containment checks, switch the Build phase to Partner, under insider-list and C4 terms, before the USD 102k is released. The Executive sponsor decides (Hypothetical). |
