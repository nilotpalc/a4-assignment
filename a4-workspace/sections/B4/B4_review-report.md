# Review report - B4 Autonomy boundaries, incident response and culture | 2026-11-08 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Strong and complete. The autonomy tier is stated honestly, the suspension trigger is observable and can be invoked from outside the delivery team, the fallback is the proven manual process, all five incident stages have an owner, notification applies only where a rule does, and the culture action has two measures. What held it back: at 265 words the table was just over the 10% budget tolerance (limit 264). What changed: four edits to trim wording, with no change to any decision or number. It is now about 263 words, after adding the incident types you asked for (limit 264).

**Rubric position (indicative, not a prediction):**
| Criterion | Before | After | Marks range before -> after (of 7) |
|---|---|---|---|
| Proportionate agent limits (Tier 1, allowed/prohibited, safe failure) | Full | Full | |
| Operational rollback and incident workflow (trigger, kill switch, fallback, 5 stages, conditional notification) | Full | Full | |
| Adoption evidence (concrete action + success indicator) | Full | Full | |
| Worksheet rules (budget +10%) | Partial (265 words) | Full (about 263, at the limit) | |
| **Overall** | | | 5.5-6.5 -> 6-7 (Estimate) |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Row 2 | Placeholder note "reset at gate 2 to about twice the peak seen in the 3-pack pilot token test" -> "reset at gate 2 to about twice the pilot peak" | Budget; your meaning kept | Brings the section within tolerance |
| 2 | Row 2 | Fallback sentence written as actions: "hold packs in progress; analysts revert to the manual process" | Budget, parallel phrasing | Same content, fewer words |
| 3 | Row 1 | "Low autonomy: Tier 1, the agent drafts and a human approves" -> "Low autonomy, Tier 1: the agent drafts, a human approves" | Budget | Same content |
| 4 | Row 3 | DPDP sentence shortened, VALIDATE kept | Budget; conditional notification kept | Notification stays conditional, as the rubric requires |
| 5 | Row 3 (learner-requested 2026-11-08) | Added incident types defined in advance: (a) wrong pack reaches the LT; (b) financial data reaches anyone not entitled to it, via the model provider, prompt injection or agent access scope. Escalation to the enterprise risk committee now tied to type (b). Rows 1-4 trimmed to fit (no meaning changed) | Course playbook: define incident types before an incident; budget | Shows the incident plan is designed for this agent's real failure modes, strengthening the incident-workflow criterion |
| - | Whole file | [GUIDE] blocks removed; your confirmed values (Yes, 150 placeholder, 1 working day, 1 near-miss a month) kept unchanged | Spec structure | Clean text ready to accept |

## Needs your input
- None. All [CONFIRM] items are resolved.

## Judgement flags (not changed)
- **Yes / Tier 1 ties C1 (X-08).** Ticking Yes is correct for a planning, tool-using agent. C1 must now describe it as a bounded, read-only agent. It must not treat that as high-risk unless a regime's tests actually apply. If C1 says "non-agentic", one of the two sections loses consistency marks.
- **Rehearsal twice a year.** The course notes recommend quarterly rehearsal. Twice a year is defensible for a 12-month pilot with about three packs a quarter (12 a year), but a marker may read it as below guidance. You could switch to "quarterly, using the quarterly sample", which costs no extra words.
- **Access scope (type b).** The agent should read only what the requesting analyst is entitled to see, not everything its service account can reach. State this control in C2 (data design) or C4 (gateway), or B4's type (b) has no matching prevention.

## Checks
- Arithmetic: no calculations in B4. The 25 analyst-days fallback matches baseline_value. PASS
- Consistency: X-07 PASS (Executive sponsor, Strategy & Analytics division lead, validation reviewer, IT security and the enterprise risk committee all appear in B2). X-08 PASS for A1 (ai_role plans and retrieves read-only); C1 is still pending. raci_incident matches: R pauses and preserves logs, A is the Executive sponsor. B3 re-runs the B1 tests before restart, which matches review_trigger_2. Training before access matches hitl_point and gate_2, and is costed in tco_b4.
- Evidence: E9 (CERT-In 6-hour direction, official site, accessed 2026-11-08) is used in row 3. Re-check that it is still current before submission. DPDP is left as VALIDATE for C2.

## Next step
- Edit v3 directly if you disagree, then /prompt-accept B4
