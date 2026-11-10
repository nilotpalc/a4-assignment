---
section: C3
title: "Build vs buy vs partner"
marks: 7
version: v1-template
generated: 2026-11-10T18:40:00+05:30
---
# C3. Build vs Buy vs Partner decision (7 marks)

> [GUIDE] Budget: 180 words beyond the comparison table (the Decision table below is drafted at about 170). Earns marks: three credible options, each with a benefit and a constraint specific to this initiative; a fit-based choice tied to A2.2 costs; an honest moat answer; one measurable factor that could reverse the choice. | Full-credit descriptor: "three credible options, fit-based sourcing, explicit factor that could reverse the choice." | "No" or "Partial" on the moat is acceptable; Build is not inherently more advanced. Edit only the response cells. Resolve every [CONFIRM].

**Comparison of the three paths**

| Option | One benefit for this initiative | Most important constraint / risk | Fit: High / Medium / Low |
|---|---|---|---|
| Build in-house | Confidential dashboards, prompts and packs stay inside the organisation's tenant (A4, C2). The workflow layer is built by the internal team on the existing AI CoE model gateway: USD 55k of reallocated effort in A2.2 bucket 2, not new cash (Ref E5). | Thin delivery team: narrow data-science roles and little MLOps (Org evidence, Course 3 self-assessment) [CONFIRM: still true?]. Upkeep lapses if the owner moves. | High [CONFIRM: your rating] |
| Buy existing tool / service | Fastest start; the vendor carries maintenance and model upgrades (Hypothetical: no tool assessed) [CONFIRM: has any off-the-shelf research tool been assessed? If so, describe the type, not the vendor]. | Unpublished price-sensitive results (Ref E13) would be processed in a vendor's service, where entitlement-scoped access and the source allowlist (C2 control 1) may not be enforceable. Licence would be new cash, not quoted (VALIDATE). | Low |
| Partner / integrate with specialist | Fills the MLOps and evaluation-harness skills gap and could shorten the path to gate 2 (Hypothetical). | Partner staff would need access to unpublished results, so insider-list registration (Ref E13); fees are new cash on top of the USD 165k; know-how may leave with the partner. | Medium |

**Decision**

| Decision | Your response |
|---|---|
| 1. Recommended approach and why | Build, narrowly [CONFIRM: your choice; your intake preference was Build]. The organisation builds only the agent workflow, source connectors and evaluation harness, and rents frontier models through the existing Microsoft Azure partnership and AI CoE model gateway (Ref E14). Highest fit: the binding constraint is data containment (A4), not features, and the build uses reallocated effort (A2.2). Compute: rent. At 12 requests a year inference is about USD 8k (Estimate, Ref E5); owned capacity could not pay back. |
| 2. Does a real proprietary data moat justify a custom build? [ ] Yes [ ] Partial [ ] No - explain | [ ] Yes [x] Partial [ ] No [CONFIRM: your tick]. The proprietary asset is over a decade of sales history in internal dashboards (Org evidence): unique and durable, but the agent only reads it. No model is trained on it, so the agent itself has no moat. The data justifies in-house containment, not a custom model. |
| 3. One dependency that could reverse the decision (economics, control, data, integration or vendor risk) | Delivery capability (control risk) [CONFIRM: or choose another dependency]. If pilot pack 1 at gate 1 (end week 6) takes more than 20 analyst-days, or fails its citation or containment checks, switch the Build phase to Partner, under insider-list and C4 terms, before the USD 102k is released. The Executive sponsor decides (Hypothetical). |

## Why this draft (guide - removed at compile)
> [GUIDE]
> - **Build in-house row** - Basis: A2.2 bucket 2 (USD 55k, internal build team, reallocated effort) and bucket 1 (existing enterprise model gateway); A4 board uncertainty 2 ("solution and workflows stay inside the organisation"); context-pack maturity self-assessment (Talent Low, build-for-release ownership risk). Justification: reviewer check "benefit AND constraint specific to the initiative"; the constraint is a real weakness, which avoids the "build as prestige" trap. Sources: knowledge part-c "Build vs buy vs partner"; context-pack organisation context. Consistency: tco_b1, tco_b2, board_uncertainty_2, sourcing_preference. Note: course notes cite in-house success of about one third vs two thirds for buy/partner; left out of the table because the notes themselves flag it as unverified.
> - **Buy row** - Basis: C2 data categories (unpublished price-sensitive results, E13) and control 1 (entitlement-scoped access); no vendor has been assessed in any accepted section, so the benefit is labelled Hypothetical and no licence price is invented. Justification: rubric Low is "buy purely on vendor claims"; the row rejects Buy on fit, not on prejudice. Sources: knowledge part-c (buy for standard capability, deployed in months - directional); context-pack sourcing logic (customer-controlled, portable governed layer). Consistency: data_categories, control_1, reg_sector.
> - **Partner row** - Basis: skills gap from the context pack; insider-list requirement from C1 sector row; A2.2 note that buckets 2-5 (USD 83k) are reallocated effort, so partner fees would be incremental cash. Justification: differentiated from Buy (different benefit, different risk), so the three ratings are High / Low / Medium, not three Mediums. Sources: knowledge part-c; context-pack contract logic (portability, exit). Consistency: reg_sector, tco_total.
> - **1. Recommended approach** - Basis: ledger sourcing_preference Build (provisional, your intake choice); ledger downstream note "C3 must reconcile Build with bought components", hence "Build, narrowly" with the rented model and gateway named; A2.2 inference USD 8k at 12 requests a year. Justification: reviewer checks "matches the highest fit and the A2.2 TCO assumptions" and "compute ownership/rental rationale present". Sources: knowledge part-a L7 (rent for pilots and low or spiky usage; own only for high, steady utilisation); part-c "build what defines your differentiation; buy or partner for the rest". Consistency: tco_b1, tco_b2, data_flow, X-10 (C4 must name Microsoft Azure and the gateway as external dependencies). EU AI Act role stays provider and deployer as in C1 (eu_ai_act_role), because the choice is still an in-house build; nothing to change there.
> - **Judgement flag (yours to decide)** - The course rule is "build only when a proprietary data moat creates durable advantage". Your moat is Partial at best, so a marker may ask why Build. The draft answers this by scoping the build to the workflow layer and justifying it on containment and cost, not differentiation. If you prefer to follow the course rule strictly, Partner (specialist builds on your gateway) is the defensible alternative; then swap the High and Medium ratings and rewrite row 1.
> - **2. Moat test** - Basis: context pack (SAP transactions captured at source for over a decade; proprietary value sits in internal dashboards, not in the agent). Justification: the pre-fill strategy asks what is proprietary and whether it is unique, durable and relevant to the model's advantage; the answer separates "unique data" from "model advantage". "No" would also be defensible and is common. Sources: knowledge part-c moat test; context-pack "Likely Assignment 4 stance". Consistency: data_categories.
> - **3. Reversal dependency** - Basis: A3 gate 1 evidence (pilot pack 1 at or under 20 analyst-days, cited, contained; end week 6) and the A4 statement that the USD 102k Build release follows a gate 1 pass. Justification: reviewer check "concrete and monitored (link to a gate)"; it reuses a threshold already accepted, so no new number enters the report. Alternatives you could choose instead: vendor risk (the Azure agreement does not confirm zero retention and no training, C2 validation item) or economics (projected inference above USD 20k a year, A2.2). Consistency: gate_1, tranche_scope, role_line1.

## To confirm before you save (guide)
> [GUIDE]
> 1. [CONFIRM] Build row constraint: is the thin-team description (narrow data-science roles, little MLOps) still true? Default: keep.
> 2. [CONFIRM] Build fit rating. Default: High (must stay the highest rating if you recommend Build).
> 3. [CONFIRM] Buy row: has any off-the-shelf tool been assessed? Default: no; keep "Hypothetical: no tool assessed" and delete the question.
> 4. [CONFIRM] Recommended approach. Default: Build, narrowly (matches your intake preference and A2.2). See the Judgement flag above before deciding.
> 5. [CONFIRM] Moat tick. Default: Partial ("No" is also defensible).
> 6. [CONFIRM] Reversal dependency. Default: delivery capability at gate 1.
