# Review report - C4 Vendor safeguards and integrated go / no-go | 2026-11-10 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Strong. You resolved all 7 [CONFIRM] items, added a fallback to gate 3 (pack 1 limited to subscribed-source and published pricing data) and stated what you understand about the source licences and the gateway's second model. What held it back was length: your additions took Table 2 to 253 words against a 200 budget. Edits cut it to 216 (tolerance 220), labelled your two "understood to" statements and tightened two sentences; no decision was changed.

**Rubric position (indicative, not a prediction):**
| Criterion | Before (v2) | After (v3) | Marks range before -> after (of 9) |
|---|---|---|---|
| Five meaningful, verifiable safeguards (none uptime-only, each with evidence to request) | Full | Full | 7-8 -> 8-9 |
| Integrated handoff: gates cite real thresholds and owners; 90-day objective covers the four tests | Full (over budget) | Full | |
| One decision that follows finance, governance, compliance and sourcing | Full | Full | |

## Changes made
| # | Where | Change (before -> after, short) | Rule / rubric basis | Why it helps you score |
|---|---|---|---|---|
| 1 | Table 2, gate 3 | Removed "so safeguards and controls are in place first"; "If this timing is not feasible" -> "If not feasible". Your fallback sentence kept in full | X-16 word budget | The cut clause repeated the sentence before it; the fallback is the part that earns credit |
| 2 | Table 2, gate 5 | "Conditional Go, equal to A4, conditional on all earlier gates being passed and all safeguards and controls validated" -> "Conditional Go, as in A4"; closing clause now "later releases wait for their gates and safeguards" | X-16; X-06 | Your condition is kept once, at the end of the sentence, instead of twice; the worksheet asks for a one-sentence rationale |
| 3 | Table 2, gate 4 | Removed "projected inference at most USD 20k a year" | X-16 | It is a cost test already required at A3 gate 2; the four named tests are all still covered |
| 4 | Table 2, gates 1, 3, 5 and caption | Moved "(Ref E7)", "(Ref E14)" and "(Hypothetical, Ref E6)" from the cells to the table caption | X-16, X-17 | Labels and references stay visible without using response words |
| 5 | Safeguard 2 | Added "(Org evidence, unverified)" to "understood to allow"; tightened the licence sentence; zero-retention sentence -> "Zero retention (safeguard 1) also keeps licensed content out of the provider's stores" | X-17 labelling; relevance to the IP row | Your understanding is shown as unverified, not as fact; the retention point now says why it matters for licensed content |
| 6 | Safeguard 2 | "Inference is about USD 8k a year" -> "First-year inference is about USD 8k" | X-10, same wording as C3 and A2.2 bucket 1 | A marker cross-checking costs finds the same figure in the same terms |
| 7 | Safeguard 5 | "contract ... multiple models ... second recommended model" -> "agreement ... several models (Org evidence, unverified) ... second model" | X-17; term "agreement" as in C2 | Same labelling point as row 5 |
| 8 | Whole file | Removed [GUIDE] blocks for the clean version | Compile rule | None on marks; housekeeping |

## Needs your input
- None. No [CONFIRM] items remain.

## Judgement flags (not changed)
- **Table 1 is long (about 740 words).** The worksheet sets no budget for it, and every row is verifiable, but the whole report is capped at 20 pages. If the compile step runs over, this table is the first place to cut: the "Evidence:" lists could be shortened.
- **Portability test adds an item to gate 2.** Safeguard 5 says one pilot pack is re-run on a second model at gate 2. A3's gate 2 evidence list does not include it. It does not contradict A3, but a strict cross-check may note it; reopening A3 is not worth it.
- **Gate 3 fallback and A3.** A3 says pilot pack 1 runs "on a live monthly request". Your fallback limits pack 1 to subscribed-source and published pricing data if the terms are not confirmed in time. That is still a live request with narrower data, so I read it as consistent; the 20 analyst-day test would then be measured on a simpler pack.
- **"Understood to allow" (licences, second model).** These are your statements and are now labelled unverified. They are honest, which the rubric rewards, but they stay open items for Legal counsel and the Head of AI CoE.

## Checks
- Arithmetic: none in this section. Figures reused, not recomputed: 5 FTE, USD 90k, 20 analyst-days, USD 25k (A3 gate 1, A4), 95% (B3), -51.5% (A2.3), USD 8k (A2.2), 25 analyst-days (A1), 12 months retention (C2). All match the ledger.
- Consistency: X-05 PASS (kill rule in the commercial gate). X-06 PASS (Conditional Go = A4; sober against Expected ROI -51.5%). X-07 PASS (Executive sponsor, validation reviewer, Head of AI CoE, IT security, Enterprise Risk Support team in B2; Legal counsel in C1). X-09 PASS (data-rights safeguard matches C2 control 2). X-10 PASS (in-house build; Microsoft Azure and the AI CoE gateway named). X-13 PASS (four tests present; match A3 gates 1-2 and C2). X-14 PASS. X-16 PASS (216 words, within tolerance). X-17 PASS.
- Evidence: no new E-id. E5, E6, E7, E9, E13, E14 reused and present in the log. One regulatory reference (CERT-In 6 hours, E9), already verified in B4 and worded as conditional. No new legal claim.
- Completeness: five safeguard rows and five handoff rows, original labels and order; none is uptime-only; each has evidence to request.

## Next step
- Edit v3 directly if you disagree, then run /prompt-accept C4.
