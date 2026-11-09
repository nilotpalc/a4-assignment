---
section: C1
title: "Regulatory applicability map"
marks: 8
version: v1-template
generated: 2026-11-09T20:58:00+05:30
---
# C1. Regulatory applicability map (8 marks)

> [GUIDE] Budget: ~220 words across the table (this draft ~217). Earns marks: only truly relevant regimes mapped, each with its legal status category (enacted / in force / commenced / draft / guideline / contractual) and a resulting design control. Full-credit descriptor: "only truly relevant jurisdictions/sectors mapped, with regulatory status and resulting controls". Low: every regime applies, invented obligations, enacted and commenced conflated. Edit only the response columns. Resolve every [CONFIRM]. Every date below was checked on secondary sources on 2026-11-09 and must be re-checked on the official source before review (VALIDATE).

| Regulatory lens | Applicable? / why | Likely obligation or question to validate | Design / operational implication | Evidence source or reviewer |
|---|---|---|---|---|
| India: DPDP Act / data protection and other relevant India rules | Limited: corporate aggregates and public sources; no customer or HR data (B1). Only staff names in logs. | DPDP Rules 2025 notified; most obligations commence 13 May 2027 (VALIDATE). CERT-In 6-hour reporting in force (Ref E9). Industrial Relations Code commenced 21 November 2025: validate for the headcount benefit, not the agent. | Ingestion filter blocks person-level fields; staff notice and log retention by May 2027; CERT-In clock in B4. | Ref E10, E12; [CONFIRM: legal reviewer]; HR legal. |
| Cross-border markets: EU AI Act, US rules or other applicable regimes | Possibly - validate: customers abroad, but packs stay internal. [CONFIRM: any LT member or user in the EU or US?] | EU AI Act in force, phased; Annex III high-risk delayed to 2 December 2027 (Regulation 2026/1744, VALIDATE). With EU users: deployer of a non-high-risk system (no decisions about people); AI-literacy duty. US: no federal AI law; state automated-decision laws not triggered (per course notes - verify). | Keep the no-person-level-decision rule; B4 training as literacy evidence; revisit if packs reach EU entities. | Ref E11; legal counsel; model provider's AI Act statement. |
| Sectoral regulation: RBI / SEBI / IRDAI / another regulator, or none | None identified: lubricants marketing is not RBI, SEBI or IRDAI-regulated; no credit, securities or insurance decisions. | If the parent is listed, packs with unpublished results may be price-sensitive under SEBI insider-trading rules [CONFIRM: listed?]. | B4 access scope; recipient log per pack; revisit if outputs feed a regulated decision. | Company secretary; legal counsel. |

Note: an applicability map for design, not a legal opinion; items marked VALIDATE need professional confirmation.

## Why this draft (guide - removed at compile)
> [GUIDE]
> - **India row** - Basis: ledger personal_data_hint = No; B1 ob_fairness (no HR data, no person-level decision); B4 incident type (b) and notification_clock_status. Justification: "Limited" rather than "Not applicable" because staff names in audit logs are personal data; saying so honestly avoids an overclaim. The headcount benefit (A2.1 benefit 2) makes employment law relevant, as ledger downstream_notes requires, but it is tied to the wider-org restructuring, not the agent. DPDP 72-hour breach clock left to C2 (VALIDATE there). Sources: knowledge part-c "India - DPDP"; web check 2026-11-09 (secondary: EY, Shardul Amarchand Mangaldas, Legal500 on DPDP; Taxmann, Bar & Bench on IR Code). Primary to verify: MeitY / PIB DPDP Rules notification; labour.gov.in IR Code notification S.O. 5320(E). Consistency: personal_data_hint, notification_clock_status, benefit_2_name.
> - **Cross-border row** - Basis: A1 says customers in and outside India; B1 sources cover Europe and Americas, which is about evidence, not users. Justification: the EU AI Act reaches where output is used, so the deciding fact is whether any LT member or user sits in the EU - only you know that. Role analysis (deployer, upstream model provider) avoids the "risk-tier claim without a role analysis" trap. Sources: knowledge part-c "EU AI Act", "US and global volatility"; web check 2026-11-09 (secondary: Cooley, Jones Walker, i-scoop on Regulation 2026/1744). Primary to verify: EUR-Lex texts of Regulation 2024/1689 and 2026/1744. Consistency: agentic = Tier 1 (B4, X-08), ob_fairness.
> - **Sector row** - Basis: sector_hint = No; context pack says no sectoral financial regulator. Justification: a reasoned "None identified" plus a revisit trigger earns full credit; the listed-company question is the one genuine adjacent rule, framed as a question, not a claim. Sources: knowledge part-c "Sector regulators in India". Consistency: B4 access-scope control.
> - **Evidence column** - E10-E12 added to the evidence log as provisional; each needs the official URL and access date before review.

## To confirm before you save (guide)
> [GUIDE]
> 1. [CONFIRM: legal reviewer] - recommended default: "Legal counsel (India)", with the company secretary for row 3.
> 2. [CONFIRM: any LT member or user in the EU or US?] - default if none: change row 2 to "Not applicable: all users in India and outputs stay internal; revisit if packs reach EU or US users". If yes: keep "Possibly - validate".
> 3. [CONFIRM: listed?] - if not listed, delete that sentence and keep "None identified".
> 4. VALIDATE (not a CONFIRM, but before review): re-check the three dates (13 May 2027, 2 December 2027, 21 November 2025) on MeitY, EUR-Lex and labour.gov.in.
