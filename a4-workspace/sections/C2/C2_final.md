---
section: C2
title: "Data, privacy, cross-border design"
marks: 6
version: reviewed
generated: 2026-11-10T16:20:00+05:30
---
# C2. Data, privacy and cross-border design (6 marks)

| Field | Your response |
|---|---|
| 1. Data categories and whether personal, sensitive/confidential, regulated or non-personal (no actual data required) | Confidential, non-personal: aggregate sales and margin dashboards (some unpublished price-sensitive results, Ref E6); LT questions, prompts, logs and packs. Licensed, non-personal: subscribed sources (untrusted). Personal, minimal: staff names and user IDs in logs. No customer or HR data (B1). |
| 2. High-level data flow: source -> processing / model/vendor -> outputs / users -> retention or deletion | (1) Allowlisted dashboards and subscribed sources (owner: Strategy & Analytics division lead) -> ingestion filter blocks person-level fields -> (2) AI CoE model gateway -> frontier models via the organisation's Azure partnership, EU region (Org evidence, Ref E6) -> (3) analyst drafts; Commercial Strategy manager approves; released to LT -> (4) gateway logs in the organisation's tenant, kept 12 months, then deleted. |
| 3. Two key controls (e.g. lawful purpose/notice/consent where required, role-based access, minimisation, retention, deletion, residency) | 1. Entitlement-scoped access: the agent reads only what the requesting analyst may see. Test: gate 2 security test requests an out-of-entitlement extract; it must fail (Hypothetical). 2. Provider terms: no training, zero retention beyond processing (Hypothetical, contract not reviewed, Ref E6), EU region. Test: gateway settings checked before gate 2; contract in C4. |
| 4. Does data cross borders or reach a third party? [ ] Yes [ ] No [ ] Unknown - what must be validated? | [x] Yes [ ] No [ ] Unknown. Third party: Microsoft Azure, EU region; packs reach EU and US LT members. Validate: EU hosting and zero-retention, no-training terms in the agreement; no DPDP country list published, Rule 15 allows transfer subject to government orders ; staff-name logs under DPDP from 13 May 2027, breach intimation without delay, then a detailed report within 72 hours (Ref E5). |
