---
section: B3
title: "Ethics review, fairness, human oversight"
marks: 8
version: v2-filled
generated: 2026-11-08T17:58:00+05:30
---
# B3. Ethics review, fairness and meaningful human oversight (8 marks)

> [GUIDE] Budget: about 260 words across the table (this draft is about 250). Earns marks: two distinct, observable triggers (one about change), a metric matched to the error that hurts most, with threshold, cadence and limits, a human who has the evidence, the time and the authority to say no, and a testable release blocker. | Full-credit descriptor: correct review triggers, fit-for-purpose outcome quality/fairness, meaningful human authority. | Edit only the "Your response" column. Resolve every [CONFIRM].

**Ethics review and oversight for the Leadership-team evidence-pack research agent (all triggers, metrics, thresholds and review steps are proposed controls, Hypothetical)**

| Control | Your response |
|---|---|
| 1. Two material ethics / risk review triggers | (1) Pre-deployment: before go-live in month 4, the validation reviewer (AI CoE Project Lead) runs the B1 tests on 3 pilot packs. Go-live needs written sign-off. (2) Material change: any change to a source, model or prompt template, or a scope change, sends the agent back for re-review within 2 working days. No pack is released until the re-review is done. |
| 2. Most consequential error or disparate outcome to monitor; fairness / quality measure (or justified N/A) | Most consequential error: a confident claim whose cited source does not support it, which then shapes an LT decision. Measure: supported-claim rate. The validation reviewer checks 20 sampled claims per pilot pack, then each quarter. Threshold at least 95% (no more than one miss in 20). Accuracy gap across sectors and regions at most 10 points (B1). No protected-group metric: no person is assessed and no HR data is held. Limits: 20 claims is a small sample, so the gap is indicative only, and China is not assessed. |
| 3. Where the human must review or intervene; evidence seen; authority to override | An analyst checks every citation and figure. The Commercial Strategy manager then approves each pack before LT release. The manager sees the source register, supporting and contrary evidence, confidence, evidence gaps and figure-to-query links, with low-confidence claims shown first. Time allowed: at least 1 working day per pack before LT release. The manager can strike claims, send a pack back or stop it, and must record why. |
| 4. One observable condition that must prevent release or trigger re-review | No release, and re-review starts, if a sample shows a supported-claim rate below 95%, any figure that does not reproduce from its saved query, or a sector or region gap above 10 points. |

## Why this draft (guide - removed at compile)
> [GUIDE]
- **1. Review triggers** - Basis: two of the four automatic triggers in the course notes (pre-deployment and material change). Justification: the triggers are distinct and observable, and one is about change, which the reviewer check requires. Each fires by itself ("smoke detector"), not on a calendar. The quarterly sample sits in row 2, so no trigger is only "periodic". Sources: knowledge: part-b L4. Consistency: gate_3 (go-live month 4 after independent validation), role_line2, escalation_trigger (source, model or prompt-template change, 2 working days), launch_blocker.
- **2. Error and metric** - Basis: the context pack names the "confident but wrong" report as the consequential error for this initiative. Justification: the metric detects that exact error. It has a threshold and a cadence, and it reuses B1's 20-claim sample and 10-point sector/region gap, which keeps B1 and B3 consistent (X-12). It justifies why no demographic metric applies and states the limits, avoiding the trap of a fairness metric built on data you do not have. Sources: knowledge: part-b L5; context-pack (delegation zones and quality control). Consistency: ob_transparency, ob_fairness, ob_explainability.
- **3. Human oversight** - Basis: course notes on meaningful oversight (equipped, trained, authorised, given time) and on engineered friction. Justification: names the reviewer role, the evidence they see, the time they have and their power to strike, return or stop. Showing low-confidence claims first and recording reasons both reduce automation bias. Sources: knowledge: part-b L6; context-pack (analyst verifies, manager approves, only a human releases). Consistency: role_line1, ob_accountability, ai_boundary.
- **4. Release blocker** - Basis: B1's "miss blocks release" tests. Justification: a testable condition on a sample with numbers, not a judgement call. Consistency: launch_blocker (validation reviewer pauses releases), ob_explainability (figures reproduce from saved queries).
- No legal or regulatory claim is made, so no E-id is needed. The course notes mention EU AI Act and RBI oversight duties, but C1 has not mapped either as applicable, so B3 does not cite them.

## Decisions confirmed (guide - removed at compile)
> [GUIDE]
1. Supported-claim threshold (rows 2 and 4): confirmed at 95% (no more than one unsupported claim in 20). B1 already blocks any claim that does not trace to an allowlisted source. This threshold covers a claim that traces to a source but is not supported by it.
2. Manager review time (row 3): confirmed at at least 1 working day per pack before LT release, so the approval is not a rubber stamp.
3. Optional third automation-bias control (sampling after 3 no-edit approvals): omitted from the report because of the word budget.
