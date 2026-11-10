# AIBP Course 4 - Assignment 4: AI Strategy Document with Business Case, Governance Framework, and Regulatory Compliance Plan

**Author:** Nilotpal Choudhury  
**Date:** 10 November 2026  
**Initiative:** Leadership-team evidence-pack research agent (I-1); all figures in USD thousands, 12-month horizon


# Part A. AI investment case (40 marks)

## A1. Define the AI investment proposition (6 marks)

| Field | Your response |
|---|---|
| Organisation / context and scope | Strategy & Analytics, Global Lubricants Sales & Marketing, anonymised integrated energy company with customers in and outside India (Org evidence). Scope: one workflow, evidence packs answering leadership-team (LT) macro and geopolitical sensitivity questions. USD thousands; 12 months. |
| Selected AI initiative and link to earlier opportunity (if any) | Leadership-team evidence-pack research agent, revising the Course 3 Strategic Bet "LT evidence-pack workflow" assessed in Course 2 (Org evidence). |
| Specific business problem, affected workflow and target users | Each LT question needs about 25 analyst-days of manual source gathering, dashboard extraction and drafting over roughly a month, so answers can miss the decision window. Users: Commercial Strategy analysts (draft), their manager (approve), LT (consume). |
| Current baseline / cost of inaction (metric, range or transparent estimate) | 25 analyst-days x 12 monthly requests (Org evidence) = about 300 analyst-days a year; at USD 0.2k a day, cost of inaction is about USD 60k a year (Estimate). Target: validated draft in ~15 analyst-days; turnaround 15-20 days (Estimate). Faster decisions should lift pipeline conversion: strategic value USD 100-125k (low) to 400-500k (best) a year (Hypothetical, Ref E1), excluded from the USD 60k and ROI. |
| Intended AI role and an important boundary: what it will not do | Agent plans research, retrieves from allowlisted dashboards and subscribed sources, drafts with citations and flags evidence gaps. It will not write back, send externally, add sources or release to the LT; an analyst verifies and only a human releases. Numbers come from deterministic queries. |
| Strategic rationale: why address it now, rather than another initiative? | Geopolitical uncertainty, rising input costs, weaker premium-product preference, margin pressure and OPEX-cut mandates demand faster LT re-prioritisation; analyst capacity is thin (2-3 part-time). Alternatives: sector-matched value cases are lower-risk but marginal; order-status exception visibility needs 12-18 months of data work. Reuses the model gateway. |
| Source / basis for the most important assumptions | E1: Course 2 assessment: baseline, turnaround, target, volume (Org evidence, directional). E1: day rate, Finance-confirmed (Estimate). E1: margin base, organisational records (Org evidence); uplift and attribution (Estimate, past initiatives). |

## A2.1. Value mechanisms and evidence (5 marks)

**Table 1. Measurable (monetisable) value, 12-month planning horizon, Expected case (USD thousands)**

| Value source | Baseline / driver | Expected measurable change | 12-month monetisation logic and evidence |
|---|---|---|---|
| Measurable benefit 1: analyst capacity released on LT evidence packs (Estimate) | 12 requests a year x ~25 analyst-days (Org evidence, Ref E1); USD 0.2k a day (Estimate, Ref E1). | Validated draft in ~15 analyst-days, saving ~10 analyst-days per request (Estimate, Ref E1). Live from month 4, after a validation gate, so 9 requests benefit (Estimate, Ref E2). | 9 x 10 x USD 0.2k = USD 18k capacity value (USD 24k at full run-rate: 12 x 10 x 0.2). Not banked on its own: this workflow alone frees only ~1.25 FTE of analyst time (300 days at ~240 days a year), and no overtime or external research spend line is evidenced. The released days are the enabling capacity for benefit 2 and are not added to it (no double count). Banked: USD 0k. |
| Measurable benefit 2: headcount reduction across the three support functions (Hypothetical, Ref E3) | Organisation-wide OPEX cut of 50% over 5 years; for these support functions the cost sits mainly in headcount, so they are actively reducing it (learner context, Hypothetical). Cost per FTE USD 48k (Org evidence, Finance-confirmed, Ref E3). The platform serves financial and qualitative information used by all three functions; the remaining difference is human judgement. No extra platform cost for the other two functions (A2.2). | 10 FTE reduction in Expected (Hypothetical: assumed for this assignment, not agreed with HR or Finance, Ref E3); 6-month reduction timeline after the month-4 go-live, so the saving starts in month 11 and 2 of 12 months fall in year 1. | 10 x USD 48k x 2/12 = USD 80k in year 1 (USD 480k annualised). The budget line that changes is function headcount cost. Attribution to the platform is unproven: the cut may happen under the OPEX mandate anyway, so the amount is conditional on HR and Finance agreeing the reduction (tested in A2.3). Severance and transition costs are excluded as wider-organisation restructuring costs and are out of scope for this benefit analysis. |
| Optional measurable benefit 3: none claimed | None. | None. | Scale-stage benefits are outside the 12-month horizon. |

**Total measurable benefit, 12 months, Expected: USD 80k (benefit 1 banked USD 0k + benefit 2 USD 80k, Hypothetical, subject to the headcount decision). USD 18k capacity value shown, not added.**

**Table 2. Strategic / not-yet-monetisable value (not counted in ROI)**

| Strategic / not-yet-monetisable value | Why it matters and how it might later be evidenced |
|---|---|
| Faster, better-timed LT decisions (Hypothetical, Ref E1) | Turnaround is targeted to fall from about a month to 15-20 days (Estimate), so answers meet the decision window. Potential USD 400-500k a year best case (25% attribution x ~USD 1.6-2M margin uplift) and USD 100-125k low case (25% of the best case); causal link unproven, so excluded from ROI. Later evidence: log each LT decision with request date, release date and linked opportunity; after two quarters compare conversion of supported and unsupported decisions. |
| Analyst capacity redeployed to higher-value analysis (Hypothetical) | ~90 released analyst-days in-year (9 x 10) could clear backlog or add scenario work. Applies only if headcount is not reduced; if it is, the capacity is already counted in benefit 2. Not banked. |

## A2.2. Total cost of ownership, six buckets (6 marks)

**Indicative first-12-month costs, Expected case (USD thousands)**

| Cost bucket taught in Course 4 | 12-month estimate (USD k) | Basis / assumptions |
|---|---|---|
| 1. Compute, licences, hosting and AI infrastructure | 22 | Model inference 8 (12 requests, agent live from month 4; routed smaller models for drafting, frontier only for synthesis) (Estimate, Ref E2). Hosting on existing enterprise model gateway, vector store, access controls, logs 14 (Estimate, Ref E2). Subscribed-source access chargebacks 0: already in the function budget, so not incremental (Ref E2). |
| 2. Implementation and integration | 55 | Read-only dashboard and source connectivity, no write-back, 45 (Estimate, Ref E2). Agent workflow, prompt templates and evaluation harness build 10 (Hypothetical). Internal build team: reallocated effort, not incremental cash. Counted here once; pipelines sit in bucket 6. |
| 3. Security, privacy, risk and governance | 10 | Access-control design and security review 4; confidentiality and prompt-injection test before go-live 3; validation sign-off and audit support 3 (Hypothetical). Not separately costed in Course 2, so added here. Internal staff: reallocated effort, not incremental cash. |
| 4. Change management, training and human escalation | 6 | Training and onboarding 4 people x 3 days x USD 0.2k = 2.4 (Estimate, Ref E1). Extra analyst time on escalated or failed packs: 9 requests x 2 days x USD 0.2k = 3.6 (Hypothetical). Reallocated effort, not new cash: routine validation is already inside the ~15 analyst-days per pack (Ref E1). |
| 5. Monitoring, model performance review and maintenance | 12 | Citation and numerical-consistency checks, evidence-gap log, residual-error tracking 7; quarterly drift and prompt/template review 5, for 9 live months (Estimate, Ref E2). Internal staff: reallocated effort, not incremental cash. |
| 6. Data preparation, cleaning and access enablement | 60 | Approved-source inventory, dashboard extracts, metadata and pipelines. Within the Course 2 range of 40-90, lower-mid because dashboards already sit in the enterprise data lake (Estimate, Ref E2). Largest bucket: 36% of total. |
| **TOTAL first-12-month cost** | **165** | 22 + 55 + 10 + 6 + 12 + 60 = 165. One-off build costs counted once, in the bucket named above. Buckets 2-5 (83, 50%) are reallocated internal effort, not new cash. Enterprise platform costs and source subscriptions funded elsewhere are excluded (Ref E2). The platform also serves the other two functions at no extra build or access cost: the deployment platform and strategy workload stay flat as duplicated project work falls (learner assumption, confirmed 2026-11-06). Costs do not depend on the headcount decision. Severance and transition costs are excluded as wider-organisation restructuring. |

**Biggest cost uncertainty and how you would test it (100 words)**

Data preparation (USD 60k, 36% of total). If extracts or metadata need more work than assumed, it could reach the top of the 40-90k range. Test: a two-week data-access spike before gate 1 inventories every source and extract and re-estimates the bucket. AI usage could change cost only slightly at 12 requests a year, but multi-step agent loops could multiply tokens. Test: run 3 pilot packs, log tokens per pack, and revisit bucket 1 if projected inference exceeds USD 20k a year. Usage-sensitive: yes; driver is tokens per evidence pack (Estimate).

## A2.3. Weak / expected / strong value cases (7 marks)


**12-month cases (USD thousands). Net benefit = measurable benefits - total costs; Simple ROI = net / costs x 100. Losses in brackets.**

| Scenario | Likelihood (%) | 12-month measurable benefits | 12-month total costs | Net benefit / (loss) | Simple ROI (%) |
|---|---|---|---|---|---|
| Weak | 25 | 0 | 195 | (195) | -100.0 |
| Expected | 50 | 80 | 165 | (85) | -51.5 |
| Strong | 25 | 240 | 170 | 70 | 41.2 |

Workings. Expected (Hypothetical, Ref E3): live month 4 and a 6-month reduction timeline, so the headcount saving starts in month 11 and 2 of 12 months count: 10 FTE x USD 48k x 2/12 = USD 80k (A2.1 benefit 2; A2.1 capacity value USD 18k is not added). Cost USD 165k (A2.2 total). Net 80 - 165 = (85); ROI (85) / 165 = -51.5%. Weak: live month 7, 6 requests x 5 days x USD 0.2k = USD 6k capacity, none banked; headcount reduction not realised within the year, so benefit 0; cost 165 + 30 (data preparation at the top of its range, 90 instead of 60) = 195 (Hypothetical). Strong (Hypothetical, Ref E3): live month 3, benefit from month 10, so 3 of 12 months count: 20 FTE x USD 48k x 3/12 = USD 240k (USD 960k annualised); cost 165 + 5 (extra inference from iteration) = 170. Net 240 - 170 = 70; ROI 70 / 170 = 41.2%. FTE counts are assumptions for this assignment; only USD 48k per FTE is Finance-confirmed (Org evidence). Severance, redundancy and transition costs are excluded as wider-organisation restructuring, out of scope. Probability-weighted net: 0.25 x (195) + 0.5 x (85) + 0.25 x 70 = (73.75), about (74). Strategic value (USD 100-125k to 400-500k a year, Ref E1) is excluded from every case.

| Question | Your response |
|---|---|
| 1. What explains the movement from Weak to Strong? | Go-live month (7, 4, 3), days saved per request (5, 10, 12), headcount reduction (none; USD 80k; USD 240k), data preparation (90, 60, 60) and inference (8, 8, 13) drive the spread (Hypothetical, Ref E2, E3). Any benefit depends on a headcount decision outside this initiative, with platform attribution unproven; if not realised, Expected net is (165). |
| 2. Indicative payback expectation, or why payback is not reached in 12 months | Weak: not reached. Expected: about USD 40k a month recovers USD 165k after 4.1 months of savings; starting in month 11, only USD 80k is recovered in 12 months and payback falls around month 15. Strong: about USD 80k a month recovers USD 170k in 2.1 months, late in month 12. Capacity value alone (USD 24k a year) needs about 6.9 years. |
| 3. What evidence would most improve confidence in your financial case? | HR and Finance confirmation of reduction numbers, timing and attribution (Ref E3); the bucket 6 data-access spike; timed analyst-days and tokens from 3 pilot packs; an LT decision log (Ref E1). |

## A3. Stage-gated funding and failure controls (9 marks)

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

## A4. Board-level recommendation and investment ask (7 marks)

**Decision request (USD thousands; TCO USD 165k; tranche equals the A3 gate 1 release; all figures Hypothetical or Estimate as labelled)**

| Decision field | Your response |
|---|---|
| 1. Place this initiative in Horizon 1 / 2 / 3 of the AI investment portfolio and explain briefly | Horizon 2, a Course 3 Strategic Bet: Expected payback is about month 15, past the horizon (Hypothetical), so quality outweighs a rushed rollout. It augments strategic thinking and yields a playbook reusable across businesses (uncosted), if data governance and metadata labelling hold. |
| 2. Decision sought: Go / Conditional Go / Hold / Stop | Conditional Go, on the row 3 conditions: headcount agreement decides the case; data governance and access decide delivery. |
| 3. Specific next funding tranche and what it buys (do not automatically request the entire 12-month TCO) | USD 25k, gate 1 only: 15.2% of TCO (about 13 cash, 12 reallocated effort, Estimate). By week 6 it buys HR and Finance in-principle agreement to at least 5 FTE, the data-access spike (bucket 6 at most USD 90k) and one cited pilot pack of at most 20 analyst-days. The USD 102k Build tranche follows only on a pass. |
| 4. Top two board-level uncertainties or decision conditions | 1. Financial: all monetised benefit is a headcount reduction HR has not agreed (10 FTE x USD 48k, Hypothetical, Ref E3); without it Expected net is (165). Gate 1 tests it; gate 2 binds it. 2. Data containment: LT questions and aggregate sales data pass through the model gateway; bought tools may aid metadata, but the solution and workflows stay inside the organisation. Gate 2 tests it; C1, C2, C4 map it. |
| 5. Executive recommendation: why this is the defensible next move | Expected ROI is -51.5%, probability-weighted net about (74), only Strong positive (Hypothetical, Ref E2, E3), so a full-year commitment is not defensible. A USD 25k step is: under 5 FTE agreed by week 6, spend stops with 85% unreleased. If agreed, the reduction is worth USD 240-480k a year, before severance. |


# Part B. Governance and responsible AI (30 marks)

## B1. Convert responsible-AI principles into design obligations (7 marks)

**Design obligations for the Leadership-team evidence-pack research agent (all obligations, tests and thresholds are proposed controls, Hypothetical; NIST AI RMF used as a guide, no certification sought, Ref E4)**

| Taught principle | Specific design obligation for this initiative | Evidence / test demonstrating the obligation is met |
|---|---|---|
| Accountability | Executive sponsor (Head of Finance) is the single accountable owner of agent outcomes; the approving manager is named on each pack; the agent holds no release permission. | Validation reviewer's quarterly audit: 100% of LT packs show a named approver; access log shows zero agent releases. A missing name blocks release. |
| Transparency | Every pack must carry an AI-assisted label and a source register listing each allowlisted source, extract date and query used. | Validation reviewer traces 20 sampled claims per pilot pack, then per quarter: label present and 100% of claims trace to an allowlisted source; any miss blocks release. |
| Explainability | Each recommendation states, in plain language, supporting and contrary evidence, confidence level and evidence gaps; every figure links to its deterministic query. | Before go-live, the validation reviewer checks all four fields and reproduces every figure in 3 pilot packs from saved queries; any gap or mismatch blocks sign-off. |
| Fairness | Agent makes no person-level decision, holds no HR data and never informs role cuts. Citation accuracy must not favour any sector (power, mining, agri-machinery) or region (India, Indonesia, Europe, Americas); China excluded (no sources). | The 20 quarterly claims span every sector and region: accuracy gap at most 10 percentage points, else release pauses. Indicative; China not assessed. |

## B2. Governance ownership, RACI and three lines of defence (8 marks)

**Minimum viable governance for the Leadership-team evidence-pack research agent (all roles, rights and triggers are proposed controls, Hypothetical)**

**Table 1. Three lines of defence**

| Field | Your response |
|---|---|
| 1. Business / first-line owner of outcomes and decisions | Executive sponsor (Head of Finance, LT member) owns outcomes and the gate calls. The Strategy & Analytics division lead builds and runs the agent. The Commercial Strategy manager approves each pack; only a human releases it to the LT. |
| 2. Second-line independent risk / compliance or model validation function | AI Centre of Excellence (AI CoE) Project Lead, the validation reviewer, outside Finance and Strategy & Analytics. The AI CoE runs the model gateway, so the reviewer sits outside the gateway team; IT security tests the gateway. Validates before go-live and samples quarterly (B1 tests). Can block go-live and pause releases. Did not build the agent. |
| 3. Third-line independent assurance / audit function (proportionate to context) | Enterprise Risk Support team for the marketing organisation: one review before gate 4 (approver and access logs, sample traces, incident log), within A3's USD 3k audit-support line. It already reviews information risk management (IRM) compliance of the organisation's digital solutions, so this extends an existing cadence. It reports to neither the Head of Finance nor the AI CoE, so it is independent of the funding and validation lines. No standing AI committee. |
| 4. Executive / board escalation body or sponsor | The function leadership team (LT) settles blocks the sponsor disputes and decides Scale. A confidentiality breach also goes to the enterprise risk committee. |

**Table 2. RACI (one Accountable role per row)**

| Decision / activity | R - Responsible | A - Accountable (ONE role) | C / I - Consulted / Informed |
|---|---|---|---|
| Approve entry into controlled pilot | Strategy & Analytics division lead | Executive sponsor | C: validation reviewer (sign-off required), function Finance manager (co-signs), Head of Business-HR (headcount evidence). I: LT |
| Review model outputs, drift or material change | Validation reviewer (AI CoE Project Lead) | Head of AI CoE | C: Strategy & Analytics division lead, Commercial Strategy manager. I: Executive sponsor, Enterprise Risk Support team |
| Contain and escalate an AI incident | Strategy & Analytics division lead (pauses the agent, preserves logs) | Executive sponsor | C: validation reviewer, IT security, Enterprise Risk Support team. I: LT, Commercial Strategy manager |

**Table 3. Escalation**

| Escalation question | Your response |
|---|---|
| What triggers escalation from operating team to independent review, and who can block launch? | Escalate to the validation reviewer within 2 working days if: an uncited or unreproducible figure reaches the LT; a sampled claim fails to trace to an allowlisted source; the fairness gap exceeds 10 points (B1); data leaves the gateway or a prompt-injection test fails; or a source, model or prompt template changes. The validation reviewer can block go-live and pause releases. IT security can block on a failed security test. The sponsor cannot overrule a block; only the LT can, on the record. |

## B3. Ethics review, fairness and meaningful human oversight (8 marks)

**Ethics review and oversight for the Leadership-team evidence-pack research agent (all triggers, metrics, thresholds and review steps are proposed controls, Hypothetical)**

| Control | Your response |
|---|---|
| 1. Two material ethics / risk review triggers | (1) Pre-deployment: before go-live in month 4, the validation reviewer (AI CoE Project Lead) runs the B1 tests on 3 pilot packs. Go-live needs written sign-off. (2) Material change: any change to a source, model, prompt template or scope triggers re-review. The validation reviewer re-runs the affected B1 tests within 2 working days. No pack is released until the re-review is done. |
| 2. Most consequential error or disparate outcome to monitor; fairness / quality measure (or justified N/A) | Most consequential error: a confident claim whose cited source does not support it, which then shapes an LT decision. Measure: supported-claim rate. The validation reviewer checks 20 sampled claims per pilot pack, then each quarter. Threshold at least 95% (no more than one miss in 20). Supported-claim gap across sectors and regions at most 10 points (B1). No protected-group metric: no person is assessed and no HR data is held. Limits: with 20 claims, one miss can breach the gap, so the gap test is deliberately strict and indicative only. China is not assessed. |
| 3. Where the human must review or intervene; evidence seen; authority to override | An analyst checks every citation and figure. The Commercial Strategy manager, trained before go-live, then approves each pack before LT release. The manager sees the source register, supporting and contrary evidence, confidence, evidence gaps and figure-to-query links, with low-confidence claims shown first. Time allowed: at least 1 working day per pack. The manager can strike claims, send a pack back or stop it, and must record why. The quarterly sample re-checks approved packs, so approval is tested, not assumed. |
| 4. One observable condition that must prevent release or trigger re-review | No release, and re-review starts, if a sample shows a supported-claim rate below 95%, any figure that does not reproduce from its saved query, or a sector or region gap above 10 points. The validation reviewer pauses releases (B2). |

## B4. Autonomy boundaries, incident response and culture (7 marks)

**Autonomy, incidents and culture for the Leadership-team evidence-pack research agent (all limits, triggers and actions are proposed controls, Hypothetical)**

| Decision | Your response |
|---|---|
| 1. Agentic/autonomous actions involved? [ ] No [ ] Yes. If yes, describe allowed and prohibited actions and autonomy level; if no, explain the applicable decision boundary. | [ ] No [x] Yes. Low autonomy, Tier 1: the agent drafts, a human approves. Allowed: plan research steps, query allowlisted dashboards and subscribed sources (read-only), draft with citations, flag gaps. Prohibited: write-back, external send, adding sources, LT release, filling gaps from model memory. On tool failure: retry once, mark a gap. |
| 2. Escalation / suspension trigger, accountable human and kill-switch or manual fallback (if relevant) | Suspend if the agent attempts a non-allowlisted source or a write action, data leaves the gateway, or tool calls exceed 150 per pack (placeholder; reset at gate 2 to twice the pilot peak). The validation reviewer or IT security can revoke the agent's gateway credentials without delivery-team approval. Accountable: Executive sponsor. Fallback: hold packs in progress; analysts revert to manual work (about 25 analyst-days a pack). |
| 3. Incident plan: detect -> contain -> escalate -> notify where applicable -> review / prevent recurrence | Owner: Executive sponsor. Types: (a) wrong pack reaches the LT; (b) financial data reaches anyone not entitled to it, via the model provider, prompt injection or agent access scope. Detect: gateway telemetry, quarterly sample, returns. Contain: Strategy & Analytics division lead pauses the agent, preserves logs, recalls any affected pack. Escalate: sponsor and validation reviewer within 1 working day; type (b) also to the enterprise risk committee. Notify where applicable: IT security reports CERT-In-listed cyber incidents within 6 hours of noticing them (Ref E4). Only staff names in logs, so a DPDP breach report is unlikely but VALIDATE in C2. Review: root cause, fix, re-run B1 tests before restart; rehearse twice yearly. |
| 4. One adoption / culture action that makes governance real (training, incentives or reporting) and how you will know it worked | Training before access: analysts and manager trace a planted unsupported claim. A near-miss log records claims struck before release. Success: 100% trained before access; at least 1 near-miss a month in the first quarter. |


# Part C. Regulation, data and sourcing (30 marks)

## C1. Regulatory applicability map (8 marks)

| Regulatory lens | Applicable? / why | Likely obligation or question to validate | Design / operational implication | Evidence source or reviewer |
|---|---|---|---|---|
| India: DPDP Act / data protection and other relevant India rules | Limited: corporate aggregates and public sources; no customer or HR data (B1); staff names in logs. | DPDP Rules notified 13 November 2025 ; most duties commence 13 May 2027. CERT-In 6-hour reporting in force (Ref E4). Industrial Relations Code in force 21 November 2025, Central Rules 8 May 2026, state rules mostly draft (VALIDATE with HR legal): headcount benefit only. | Ingestion filter blocks person-level fields; staff notice and log retention by 13 May 2027; CERT-In clock. | Ref E5; legal counsel; HR legal. |
| Cross-border markets: EU AI Act, US rules or other applicable regimes | Likely yes, limited (VALIDATE): EU and US LT members use the packs. | EU AI Act in force; Regulation (EU) 2026/1744 moves Annex III duties to 2 December 2027. In-house build: provider and deployer of a non-high-risk; AI-literacy duty softened to supporting measures. US: no federal AI law; state laws not triggered (verify). | No-person-level-decision rule; B4 training as literacy evidence. | Ref E5; legal counsel; model provider statement. |
| Sectoral regulation: RBI / SEBI / IRDAI / another regulator, or none | None: lubricants marketing is not RBI, SEBI or IRDAI-regulated. | European and US listings bring insider-trading rules in scope for packs with unpublished results; SEBI's do not (nothing listed in India; VALIDATE). Insider list covers India staff (Org evidence, Ref E6). | Recipients of unpublished results join the insider list; recipient log per pack. | Ref E6; company secretary; legal counsel. |

Note: an applicability map for design, not a legal opinion; items marked VALIDATE need professional confirmation.

## C2. Data, privacy and cross-border design (6 marks)

| Field | Your response |
|---|---|
| 1. Data categories and whether personal, sensitive/confidential, regulated or non-personal (no actual data required) | Confidential, non-personal: aggregate sales and margin dashboards (some unpublished price-sensitive results, Ref E6); LT questions, prompts, logs and packs. Licensed, non-personal: subscribed sources (untrusted). Personal, minimal: staff names and user IDs in logs. No customer or HR data (B1). |
| 2. High-level data flow: source -> processing / model/vendor -> outputs / users -> retention or deletion | (1) Allowlisted dashboards and subscribed sources (owner: Strategy & Analytics division lead) -> ingestion filter blocks person-level fields -> (2) AI CoE model gateway -> frontier models via the organisation's Azure partnership, EU region (Org evidence, Ref E6) -> (3) analyst drafts; Commercial Strategy manager approves; released to LT -> (4) gateway logs in the organisation's tenant, kept 12 months, then deleted. |
| 3. Two key controls (e.g. lawful purpose/notice/consent where required, role-based access, minimisation, retention, deletion, residency) | 1. Entitlement-scoped access: the agent reads only what the requesting analyst may see. Test: gate 2 security test requests an out-of-entitlement extract; it must fail (Hypothetical). 2. Provider terms: no training, zero retention beyond processing (Hypothetical, contract not reviewed, Ref E6), EU region. Test: gateway settings checked before gate 2; contract in C4. |
| 4. Does data cross borders or reach a third party? [ ] Yes [ ] No [ ] Unknown - what must be validated? | [x] Yes [ ] No [ ] Unknown. Third party: Microsoft Azure, EU region; packs reach EU and US LT members. Validate: EU hosting and zero-retention, no-training terms in the agreement; no DPDP country list published, Rule 15 allows transfer subject to government orders ; staff-name logs under DPDP from 13 May 2027, breach intimation without delay, then a detailed report within 72 hours (Ref E5). |

## C3. Build vs Buy vs Partner decision (7 marks)

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

## C4. Vendor safeguards and integrated go / no-go (9 marks)

**Table 1. Minimum safeguards for the external dependencies of a narrow in-house build**

The build is in-house (C3), so there is no new vendor contract. The external dependencies are the frontier models rented through the organisation's Microsoft Azure partnership, reached through the AI CoE model gateway (Ref E6), and the licensed subscribed sources. The organisation's agreement has not been reviewed for this assignment, so every requirement below is a proposed minimum to confirm in the existing agreement or to add to it (Hypothetical). The same terms would apply to a specialist if the C3 reversal to Partner is triggered.

| AI-specific safeguard taught in Course 4 | Minimum requirement / evidence to request | Why it matters for this initiative |
|---|---|---|
| 1. Data rights and permitted model training / retention / subprocessing | No training on prompts, extracts or outputs; zero retention beyond processing, including any provider-side monitoring or logging copies; EU-region processing; named sub-processors with notice of change. Evidence: the data-processing clauses, the current sub-processor list, and a gateway configuration export showing region and retention settings, supplied by the Head of AI CoE and read by Legal counsel. | C2 control 2 rests on these terms, and they are assumed, not seen (Ref E6). Prompts carry unpublished price-sensitive results (Ref E6); a retained copy is B4 incident type (b). |
| 2. Intellectual-property risk, indemnity and liability allocation | Provider indemnity for third-party IP claims on outputs, confirmed to cover use through the gateway. Liability for confidentiality breach or data misuse not capped at fees paid. The organisation owns prompts, packs, connectors and the evaluation harness. The subscribed-source agreements are understood to allow use of their content in internal AI tools (Org evidence, unverified); the terms of each allowlisted licence must be reviewed and each vendor's confirmation sought (VALIDATE with Legal counsel). Zero retention (safeguard 1) also keeps licensed content out of the provider's stores. Evidence: indemnity and liability clauses; licence terms checked by Legal counsel; written confirmation from each subscribed-source vendor. | Packs quote licensed sources and go to the LT. First-year inference is about USD 8k (Estimate, Ref E2), so a fee-based cap would be trivial against the harm of a leak of unpublished results. |
| 3. Performance SLAs beyond uptime: output quality, drift and remedies | The provider will not warrant the quality of this workflow, so the quality bar is internal: supported-claim rate at least 95% on 20 sampled claims and every figure reproducible (B3). Requirement on the provider: advance written notice of model retirement or version change, and version pinning where offered. Remedy: any model change triggers the B3 re-test before release; below 95%, releases pause and the manual process resumes. Evidence: provider model-lifecycle policy; gateway change log; evaluation-harness results per model version. | The key error is a confident claim its source does not support (B3). Uptime says the model is on, not that it is right; a silent model change is the likeliest cause of drift here. |
| 4. Audit, assurance, incident support and compliance evidence access | Current independent assurance reports for the hosting service; written confirmation that the no-training and retention terms reach through to the model developer behind the cloud service; provider notice of any incident affecting the organisation's data within 24 hours, with logs (Hypothetical). Gateway logs open to the validation reviewer, IT security and the Enterprise Risk Support team. Evidence: assurance reports; incident-support clause; one log-access test before go-live. | Accountability stays with the organisation (B1). The CERT-In 6-hour clock (Ref E4, conditional) and the B4 playbook need provider facts fast; the third-line review before gate 4 needs logs. |
| 5. Exit / portability / deletion / continuity arrangements | Prompts, workflow, connectors, evaluation harness and logs stay in the organisation's tenant in provider-neutral form. Written deletion confirmation at termination; 90 days of transition support. Portability test at gate 2: one pilot pack re-run on a second model through the gateway, scored on the same harness. The Microsoft Azure agreement is understood to allow several models on the gateway (Org evidence, unverified); availability and fit of the second model are validated with the provider at gate 2 (Hypothetical). Continuity: manual process, about 25 analyst-days a pack (B4). Evidence: deletion and transition clauses; portability-test result. | "Build, narrowly" rents the model (C3), so the model is the one part the organisation does not control. A tested switch keeps the C3 reversal real and the monthly LT pack running. |

**Table 2. Integrated design-to-execution handoff (USD thousands; all gates, tests and thresholds are proposals, Hypothetical, Ref E2, E3, E6)**

| Final decision gate | Your response |
|---|---|
| 1. Commercial gate: which A2/A3 result must be demonstrated before further funding? | A3 gate 1, end of week 6: HR and Finance agree in writing, in principle, to at least 5 FTE; bucket 6 at or below USD 90k; pilot pack 1 within 20 analyst-days. Otherwise the Executive sponsor stops at about USD 25k. |
| 2. Governance gate: which B2-B4 control must be operational before live use? | Before month-4 go-live, the validation reviewer signs off the B1 tests on 3 pilot packs and completes one credential-revocation drill. The sponsor cannot overrule a block. |
| 3. Regulatory / vendor gate: what must be confirmed or contracted before deployment? | Before pilot pack 1 uses unpublished results: safeguard 1 terms confirmed in the agreement and gateway settings. If not feasible, pack 1 is limited to subscribed-source and published pricing data. Before go-live: Legal counsel closes the C1 and C2 validation items; source licences permit AI use. |
| 4. Bounded 90-day validation objective: how will the next team test data containment, supplier/model performance, human intervention, and decision logging? | By day 90 (gate 2), on 3 pilot packs. Containment: an out-of-entitlement request and a prompt-injection test both fail. Model performance: packs average at most 20 analyst-days; supported-claim rate at least 95%. Human intervention: reviewers catch a planted unsupported claim; the suspension drill works. Logging: every pack has a named approver, source register and logged overrides, kept 12 months. |
| 5. Integrated decision: Go / Conditional Go / Hold / Stop and a one-sentence rationale | Conditional Go, as in A4. Expected ROI is -51.5%, governance controls are designed but not operating, and provider terms and four legal items are unconfirmed, so only the USD 25k gate 1 step is justified; later releases wait for their gates and safeguards. |


## Evidence and Assumptions Reference Log


| ID | Topic / claim | Type: real / hypothetical / internal | Source title, date or assumption basis | URL (if public) | Used in |
|---|---|---|---|---|---|
| E1 | Baseline and value: ~25 analyst-days per LT request, 12 requests/yr, target ~15 days; analyst day rate USD 0.2k; strategic value USD 100-125k to 400-500k/yr | internal + hypothetical | Course 2 assessment (directional); day rate confirmed by function Finance manager 2026-11-06; margin base Org evidence (anonymised); 25% attribution and 25% minimum success rate are learner Estimates | - | A1, A2.1, A2.2, A2.3 |
| E2 | Cost and scenario assumptions: annual cost ranges (total 90-270k), go-live month 4, A3 phasing 25/102/38, Weak/Expected/Strong drivers and 25/50/25 likelihoods | internal + hypothetical | Course 2 cost assessment; learner planning assumptions confirmed 2026-11-06 and 2026-11-07 | - | A2.1, A2.2, A2.3, A3, A4, C3, C4 |
| E3 | Headcount benefit: USD 48k per FTE (Finance-confirmed); 10 / 20 FTE, 6-month timing and 5-FTE kill threshold are assumptions; HR agreement not obtained | internal + hypothetical | Finance confirmation and learner statement 2026-11-06 | - | A2.1, A2.3, A3, A4, C4 |
| E4 | Governance and incident framework: NIST AI RMF 1.0 (voluntary guide); ISO/IEC 42001:2023 noted, not pursued; CERT-In 6-hour incident reporting direction (28 Apr 2022) | real | NIST AI 100-1 / AI RMF; ISO 42001 explainer; CERT-In Directions 20(3)/2022; accessed 2026-11-07 and 2026-11-08 | https://airc.nist.gov/airmf-resources/airmf/ ; https://www.iso.org/insights/iso-42001-explained ; https://www.cert-in.org.in/PDF/CERT-In_Directions_70B_28.04.2022.pdf | B1, B4, C1, C4 |
| E5 | Regulation: India DPDP Act 2023 and Rules 2025 (notified 13 Nov 2025; most duties from 13 May 2027); EU AI Act with Digital Omnibus (Annex III to 2 Dec 2027, Art 50 from 2 Aug 2026); India Industrial Relations Code (in force 21 Nov 2025; Central Rules 8 May 2026, state rules mostly draft; headcount benefit only) | real | PIB DPDP backgrounder; Regulation (EU) 2026/1744 on EUR-Lex, read through a summarising fetch by an AI-assisted tool; DPDP rule text via a mirror of G.S.R. 846(E); PRS note on the IR Central Rules. All accessed 2026-11-10. IR Code commencement (S.O. 5320(E)) and later notifications not checked against the primary text: to validate | https://static.pib.gov.in/WriteReadData/specificdocs/documents/2025/nov/doc20251117695301.pdf ; https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng (primary, read via summarising fetch) ; https://prsindia.org/billtrack/industrial-relations-central-rules-2026 | C1, C2 |
| E6 | Organisation and sourcing facts: parent listed in Europe and US, no Indian listing, insider list in place; model gateway via Microsoft Azure EU region (Org evidence); zero retention and no training are a hypothetical assumption | internal + hypothetical | Learner statements in C1 and C2 v2, 2026-11-10; legal applicability to validate with company secretary; retention terms to be confirmed in contract | - | C1, C2, C3, C4 |

## Academic Integrity and AI-Assistance Disclosure


Use AI assistance only within applicable programme academic-integrity requirements. Do not upload restricted organisational or personal data into public AI services. You are responsible for the accuracy of every claim, assumption, calculation, reference and recommendation.

| Disclosure field | Your response |
|---|---|
| 1. Did you use an AI tool? [ ] No [X] Yes | Yes, I used AI assistance throughout the project, as documented in the action log. |
| 2. If yes, name the tool(s) and describe the assistance | Claude (Anthropic) through Claude Code. It pre-filled section templates from the embedded course notes and my earlier work, ran arithmetic and consistency checks, kept the facts ledger and evidence log, checked regulatory sources through web search (secondary sources unless stated in X1), and helped compile the report. |
| 3. What did you independently check, substantively revise or judge? | Company-linked analysis, final facts affecting my proposed judgement and web links to regulatory sources (accessed through AI assistance), all checked for validity and in existence and confirmed by me. |

### Honour Declaration

- [X] The work, analysis and judgement represented in this submission are my own, subject to disclosed assistance.
- [X] Organisational facts are accurate to the best of my knowledge; estimates, anonymisation and hypothetical contexts are clearly labelled.
- [X] Financial figures, vendor evidence and regulatory claims have not been fabricated or presented with misleading certainty.
- [X] I have not shared confidential, personal or proprietary information without permission.
- [X] I understand this is an academic design exercise, not legal advice, funding approval or an executed pilot.

| Name | Date | Signature / typed acknowledgement |
|---|---|---|
| Nilotpal Choudhury | 11-Nov-2026 | Nilotpal Choudhury |
