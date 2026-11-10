---
section: B4
title: "Autonomy boundaries, incident response and culture"
marks: 7
version: final
generated: 2026-11-08T18:55:00+05:30
---
# B4. Autonomy boundaries, incident response and culture (7 marks)

**Autonomy, incidents and culture for the Leadership-team evidence-pack research agent (all limits, triggers and actions are proposed controls, Hypothetical)**

| Decision | Your response |
|---|---|
| 1. Agentic/autonomous actions involved? [ ] No [ ] Yes. If yes, describe allowed and prohibited actions and autonomy level; if no, explain the applicable decision boundary. | [ ] No [x] Yes. Low autonomy, Tier 1: the agent drafts, a human approves. Allowed: plan research steps, query allowlisted dashboards and subscribed sources (read-only), draft with citations, flag gaps. Prohibited: write-back, external send, adding sources, LT release, filling gaps from model memory. On tool failure: retry once, mark a gap. |
| 2. Escalation / suspension trigger, accountable human and kill-switch or manual fallback (if relevant) | Suspend if the agent attempts a non-allowlisted source or a write action, data leaves the gateway, or tool calls exceed 150 per pack (placeholder; reset at gate 2 to twice the pilot peak). The validation reviewer or IT security can revoke the agent's gateway credentials instantly, without delivery-team permission. Accountable: Executive sponsor. Fallback: hold packs in progress; analysts revert to manual work (about 25 analyst-days a pack). |
| 3. Incident plan: detect -> contain -> escalate -> notify where applicable -> review / prevent recurrence | Owner: Executive sponsor. Types: (a) wrong pack reaches the LT; (b) financial data reaches anyone not entitled to it, via the model provider, prompt injection or agent access scope. Detect: gateway telemetry, quarterly sample, returns. Contain: Strategy & Analytics division lead pauses the agent, preserves logs, recalls any affected pack. Escalate: sponsor and validation reviewer within 1 working day; type (b) also to the enterprise risk committee. Notify where applicable: IT security reports CERT-In-listed cyber incidents within 6 hours of noticing them (Ref E4). Only staff names in logs, so a DPDP breach report is unlikely but VALIDATE in C2 (Rules apply from 13 May 2027). Review: root cause, fix, re-run B1 tests before restart; rehearse twice yearly. |
| 4. One adoption / culture action that makes governance real (training, incentives or reporting) and how you will know it worked | Hands-on training before access: analysts and manager trace a planted unsupported claim. A near-miss log records claims struck before release. Success: 100% trained before access; at least 1 near-miss a month in the first quarter. |
