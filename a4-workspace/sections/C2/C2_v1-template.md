---
section: C2
title: "Data, privacy, cross-border design"
marks: 6
version: v1-template
generated: 2026-11-10T16:01:10+05:30
---
# C2. Data, privacy and cross-border design (6 marks)

> [GUIDE] Budget: no stated limit; keep it proportionate, about 150-200 words across the table. Earns marks: a traceable data-to-vendor-to-output lifecycle, two material and testable controls on the riskiest hop, and an honest transfer answer. | Full-credit descriptor: "traceable data-to-vendor-to-output lifecycle with two material controls and realistic transfer risk." | Edit only the "Your response" column. Resolve every [CONFIRM].

| Field | Your response |
|---|---|
| 1. Data categories and whether personal, sensitive/confidential, regulated or non-personal (no actual data required) | Confidential, non-personal: aggregate sales and margin dashboards (some unpublished price-sensitive results, Ref E13); LT questions, prompts, agent logs and packs. Licensed, non-personal: subscribed sources (untrusted content). Personal, minimal: staff names and user IDs in logs. No customer or HR data (B1). |
| 2. High-level data flow: source -> processing / model/vendor -> outputs / users -> retention or deletion | (1) Allowlisted dashboards and subscribed sources (owner: Strategy & Analytics division lead) -> ingestion filter blocks person-level fields -> (2) enterprise model gateway (AI CoE), calling [CONFIRM: internal hosted model, or external provider API; region] -> (3) draft to analyst; Commercial Strategy manager approves; released to LT, including EU and US members -> (4) prompts and logs kept [CONFIRM: 12 months] then deleted; packs per records policy. |
| 3. Two key controls (e.g. lawful purpose/notice/consent where required, role-based access, minimisation, retention, deletion, residency) | 1. Entitlement-scoped access: the agent reads only what the requesting analyst may see. Test: gate 2 security test requests an out-of-entitlement extract; it must fail (Hypothetical). 2. Provider terms: no training on prompts or outputs, retention [CONFIRM: zero / up to 30 days], named sub-processors and region; checked against gateway settings before gate 2; contract in C4 (Hypothetical). |
| 4. Does data cross borders or reach a third party? [ ] Yes [ ] No [ ] Unknown - what must be validated? | [x] Unknown [CONFIRM: tick Yes if the gateway calls an external provider]. Packs reach EU and US LT members. Validate: provider processing and retention location; DPDP transfer-restriction list (per course notes - VALIDATE); staff-name logs under DPDP from about May 2027, including 72-hour breach reporting (Ref E10, VALIDATE). |

## Why this draft (guide - removed at compile)
> [GUIDE]
> - **1. Data categories** - Basis: A1 ai_role (dashboards + subscribed sources), B1 fairness row (no HR/customer data), C1 India row (staff names in logs only), C1 sector row (unpublished results, insider list). Justification: rubric "Low" is "no data categories"; naming prompts/logs as data avoids the common trap, and treating subscribed content as untrusted links to B4 prompt-injection. Sources: knowledge part-c "Not applicable test" and "Cross-border" (confidentiality question); context-pack lethal-trifecta. Consistency: personal_data_hint No, reg_india, reg_sector, ob_fairness.
> - **2. Data flow** - Basis: A2.2 bucket 1 (existing enterprise model gateway), B2 (AI CoE runs gateway), B3 hitl_point, C1 cross-border row (EU/US LT members). Justification: rubric Full needs every hop with an owner and an explicit vendor/model hop; ledger downstream_notes requires C2 to state whether the gateway uses an external model, hence the [CONFIRM]. Retention hop closes the lifecycle. Sources: knowledge part-c "Map every copy of data... overseas processing and overseas retention are different". Consistency: role_line1/2, hitl_point, reg_crossborder, board_uncertainty_2.
> - **3. Two controls** - Basis: ledger downstream_notes (C2/C4 must state access-scope control and provider retention/no-training terms, matching B4 incident type (b)). Justification: both sit on the riskiest hops (agent access and model provider) and each has a pass/fail test tied to A3 gate 2, so they are "material and testable", not "we follow policy". Sources: knowledge part-c AI contracts (data rights: no training, no unauthorised retention, restricted sub-processing); context-pack sourcing logic. Consistency: incident_stages (b), gate_2 security test, X-09, X-13.
> - **4. Cross-border / third party** - Basis: C1 reg_crossborder (packs used in EU/US), unknown model hosting. Justification: spec allows Unknown if the validation action is named; honesty beats a convenient No. Legal claims: DPDP Rule 7 detailed breach report within 72 hours, applying from about 13 May 2027 (secondary sources checked 2026-11-10: DSCI brief, India Briefing; Gazette not checked -> VALIDATE); DPDP section 16 negative-list transfer approach from course notes only, not verified -> VALIDATE. Consistency: X-09 with C1 India and cross-border rows; C4 data-rights safeguard must repeat the provider terms.

## To confirm before you save (guide)
> [GUIDE]
> 1. Row 2: does the gateway call an internal hosted model or an external provider API, and in which region? Recommended: state what AI CoE actually runs; if unsure, write "external provider via gateway, region to confirm" (the more cautious design assumption).
> 2. Row 2: log retention period. Recommended default: 12 months (covers quarterly sampling and the twice-yearly incident rehearsal in B4).
> 3. Row 3: provider retention term. Recommended: zero retention if the enterprise agreement offers it; otherwise up to 30 days for abuse monitoring, no training.
> 4. Row 4: tick. Recommended: Yes if the gateway calls an external provider (third party, and possibly overseas); Unknown only until AI CoE confirms. Keep it consistent with C1 (Likely yes) and C4.
