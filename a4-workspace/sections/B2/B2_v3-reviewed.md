---
section: B2
title: "Governance, RACI, three lines of defence"
marks: 8
version: v3-reviewed
generated: 2026-11-08T17:00:00+05:30
---
# B2. Governance ownership, RACI and three lines of defence (8 marks)

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
