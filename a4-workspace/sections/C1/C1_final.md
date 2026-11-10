---
section: C1
title: "Regulatory applicability map"
marks: 8
version: reviewed
generated: 2026-11-10T16:05:00+05:30
---
# C1. Regulatory applicability map (8 marks)

| Regulatory lens | Applicable? / why | Likely obligation or question to validate | Design / operational implication | Evidence source or reviewer |
|---|---|---|---|---|
| India: DPDP Act / data protection and other relevant India rules | Limited: corporate aggregates and public sources; no customer or HR data (B1); staff names in logs. | DPDP Rules notified 13 November 2025 ; most duties commence 13 May 2027. CERT-In 6-hour reporting in force (Ref E4). Industrial Relations Code in force 21 November 2025, Central Rules 8 May 2026, state rules mostly draft (VALIDATE with HR legal): headcount benefit only. | Ingestion filter blocks person-level fields; staff notice and log retention by 13 May 2027; CERT-In clock. | Ref E5; legal counsel; HR legal. |
| Cross-border markets: EU AI Act, US rules or other applicable regimes | Likely yes, limited (VALIDATE): EU and US LT members use the packs. | EU AI Act in force; Regulation (EU) 2026/1744 moves Annex III duties to 2 December 2027. In-house build: provider and deployer of a non-high-risk; AI-literacy duty softened to supporting measures. US: no federal AI law; state laws not triggered (verify). | No-person-level-decision rule; B4 training as literacy evidence. | Ref E5; legal counsel; model provider statement. |
| Sectoral regulation: RBI / SEBI / IRDAI / another regulator, or none | None: lubricants marketing is not RBI, SEBI or IRDAI-regulated. | European and US listings bring insider-trading rules in scope for packs with unpublished results; SEBI's do not (nothing listed in India; VALIDATE). Insider list covers India staff (Org evidence, Ref E6). | Recipients of unpublished results join the insider list; recipient log per pack. | Ref E6; company secretary; legal counsel. |

Note: an applicability map for design, not a legal opinion; items marked VALIDATE need professional confirmation.
