---
section: B2
title: "Governance, RACI, three lines of defence"
marks: 8
version: v1-template
generated: 2026-11-08T16:00:00+05:30
---
# B2. Governance ownership, RACI and three lines of defence (8 marks)

> [GUIDE] No fixed word budget; keep it to about 300 words across the three tables (the course warns against committee sprawl). Earns marks: explicit ownership, credible independence and a workable escalation path. Full-credit descriptor: one accountable owner per decision, independent challenge, workable escalation. Partial: roles overlap, weak independence or ambiguous decisions. Low: all ownership given to vendor/IT without independent oversight. Use role titles, not names. Edit the response cells only. Resolve every [CONFIRM].

**Minimum viable governance for the Leadership-team evidence-pack research agent (all roles, rights and triggers are proposed controls, Hypothetical)**

**Table 1. Three lines of defence**

| Field | Your response |
|---|---|
| 1. Business / first-line owner of outcomes and decisions | Executive sponsor (Head of Finance, LT member) owns outcomes and the gate calls. The Strategy & Analytics division lead builds and runs the agent. The Commercial Strategy manager approves each pack; only a human releases it to the LT. |
| 2. Second-line independent risk / compliance or model validation function | The AI Center of Excellence (AI CoE) Project Lead (the "validation reviewer") serves as the second-line function, reviewing the quality of the evidence pack and model outputs. Sits outside Finance and Strategy & Analytics. Validates before go-live and samples quarterly (B1 tests). Can block go-live and pause releases. Did not build the agent. |
| 3. Third-line independent assurance / audit function (proportionate to context) | The Enterprise Risk Support team supporting the marketing organisation conducts one review before gate 4 (approver and access logs, sample traces, incident log), within A3's USD 3k audit-support line. The team already reviews IRM compliance within digital solutions for the marketing organisation, so this is a logical extension of its current digital cadence responsibilities. No standing AI committee. |
| 4. Executive / board escalation body or sponsor | The function leadership team (LT) settles blocks the sponsor disputes and decides Scale. A confidentiality breach also goes to the enterprise risk committee [CONFIRM: escalation body names]. |

**Table 2. RACI (one Accountable role per row)**

| Decision / activity | R - Responsible | A - Accountable (ONE role) | C / I - Consulted / Informed |
|---|---|---|---|
| Approve entry into controlled pilot | Strategy & Analytics division lead | Executive sponsor | C: validation reviewer (sign-off required), function Finance manager (co-signs), Head of Business-HR (headcount evidence). I: LT |
| Review model outputs, drift or material change | Validation reviewer (AI CoE Project Lead) | AI CoE Project Lead | C: Strategy & Analytics division lead, Commercial Strategy manager. I: Executive sponsor, Enterprise Risk Support team |
| Contain and escalate an AI incident | Strategy & Analytics division lead (pauses the agent, preserves logs) | Executive sponsor | C: AI CoE Project Lead (validation reviewer), IT security, Enterprise Risk Support team. I: LT, Commercial Strategy manager |

**Table 3. Escalation**

| Escalation question | Your response |
|---|---|
| What triggers escalation from operating team to independent review, and who can block launch? | Escalate to the validation reviewer within 2 working days if: an uncited or unreproducible figure reaches the LT; a sampled claim fails to trace to an allowlisted source; the fairness gap exceeds 10 points (B1); data leaves the gateway or a prompt-injection test fails; or a source, model or prompt template changes. The validation reviewer can block go-live and pause releases. IT security can block on a failed security test. The sponsor cannot overrule a block; only the LT can, on the record. |

## Why this draft (guide - removed at compile)
> [GUIDE]
> - **Shape** - Basis: the course's minimum viable structure: one executive who owns AI risk, one independent reviewer who did not build the model, a review on the calendar. "The full structure is a destination, not an entry price." Board risk committee and AI council are scaled down to the LT and one reviewer. Sources: knowledge: part-b L3; earlier work: context pack (Process Low; no structured ownership, so ownership is designed explicitly). Consistency: X-07.
> - **Line 1** - Basis: A3 and B1 already make the Executive sponsor the go / hold / kill owner and the single accountable owner of outcomes. The division lead builds; the approving manager releases. This separates "who builds" from "who owns". Sources: knowledge: part-b L1, L3. Consistency: gate_1 to gate_3, ob_accountability, users, ai_boundary.
> - **Line 2** - Basis: "the players can never referee their own game". The sponsor leads the function whose Finance team confirmed USD 48k per FTE (carried judgement flag from B1), so the reviewer must sit outside both Finance and Strategy & Analytics. If no such function exists, the course allows the closest independent function or an outside validator; say which. Justification: an explicit right to block go-live is what makes second-line independence credible. Sources: knowledge: part-b L3. Consistency: A3 gate 2 ("validation reviewer outside the build team named"), gate 3 sign-off.
> - **Line 3** - Basis: proportionate assurance; one review timed to the Scale decision rather than a standing committee. Already costed in A3 gate 3 (validation sign-off and audit support USD 3k), so no new cost. Sources: knowledge: part-b L3. Consistency: gate_3, gate_4, tco_total.
> - **Line 4** - Basis: the LT already decides Scale in A3 gate 4. Sending a confidentiality breach upward keeps it consistent with A4 board uncertainty 2 (data containment). Consistency: board_uncertainty_2, gate_4.
> - **RACI row 1** - The sponsor is A; the reviewer is C with a required sign-off, so A and the challenger are different roles. The function Finance manager and Head of Business-HR roles match A3 gates 1-2.
> - **RACI row 2** - The taught pattern puts independent validation under the second line, which is both R and A here (course example: second-line team R, CRO A). Making the sponsor A here would let the owner referee their own outputs.
> - **RACI row 3** - The sponsor stays A for incidents because they own outcomes; the division lead contains. B4 must use the same incident owner and kill-switch holder.
> - **Escalation** - Every trigger is an observable event taken from B1 tests, A3 gate 2 security tests or a change event. The "2 working days" timing is my suggestion. A block that only the LT can lift, on the record, is a workable path: neither the sponsor nor the builder can bypass it. Consistency: ob_transparency, ob_explainability, ob_fairness.
> - **Not used** - No vendor or IT role owns outcomes. IT security is consulted and holds a narrow, test-based block only.

## To confirm before you save (guide)
> [GUIDE]
> 1. **Second-line function** - RESOLVED: AI Center of Excellence (AI CoE) Project Lead (team name anonymised for the final report); used in Table 1 row 2 and RACI row 2.
> 2. **Internal Audit review** - RESOLVED: Enterprise Risk Support team supporting the marketing organisation, one review before gate 4.
> 3. **Escalation bodies** - Recommended: the function LT plus the enterprise risk committee for confidentiality breaches only. Use the names your organisation uses, anonymised.
> 4. **2 working days** timing and **"the sponsor cannot overrule a block"** - CONFIRMED by the learner.
