---
section: C1
title: "Regulatory applicability map"
marks: 8
version: v2-filled
generated: 2026-11-10T10:30:00+05:30
---
# C1. Regulatory applicability map (8 marks)

| Regulatory lens | Applicable? / why | Likely obligation or question to validate | Design / operational implication | Evidence source or reviewer |
|---|---|---|---|---|
| India: DPDP Act / data protection and other relevant India rules | Limited: corporate aggregates and public sources; no customer or HR data (B1). Only staff names in logs. | DPDP Rules notified 14 November 2025; most obligations commence about mid-May 2027 (18 months); consent managers from 14 November 2026 (VALIDATE). CERT-In 6-hour reporting in force (Ref E9). Industrial Relations Code in force 21 November 2025, rules to confirm (VALIDATE): affects the headcount benefit, not the agent. | Ingestion filter blocks person-level fields; staff notice, log retention by May 2027; CERT-In clock (B4). | Ref E10, E12; Legal counsel (India); HR legal. |
| Cross-border markets: EU AI Act, US rules or other applicable regimes | Possibly - validate: EU and US LT members use internal packs; board members receive released packs only, no agent access. | EU AI Act in force, phased; Regulation (EU) 2026/1744 moves Annex III duties to 2 December 2027 (VALIDATE). In-house build: provider and deployer of a non-high-risk system (no decisions about people); AI-literacy duty (check amended wording). US: no federal AI law; state decision laws not triggered (per notes - verify). | No-person-level-decision rule; B4 training as literacy evidence; revisit if packs reach customers. | Ref E11; legal counsel; model provider statement. |
| Sectoral regulation: RBI / SEBI / IRDAI / another regulator, or none | None identified: lubricants marketing is not RBI, SEBI or IRDAI-regulated. | European and US listings bring those insider-trading rules into scope for packs with unpublished results; SEBI's do not, as nothing is listed in India (validate). Existing insider list covers India staff (Org evidence, Ref E13). | Recipients of unpublished results join the insider list; recipient log per pack. | Ref E13; company secretary; legal counsel. |

Note: an applicability map for design, not a legal opinion; items marked VALIDATE need professional confirmation.
