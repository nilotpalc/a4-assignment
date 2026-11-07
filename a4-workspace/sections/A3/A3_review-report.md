# Review report - A3 Stage-gated funding and failure controls | 2026-11-07 | v2-filled -> v3-reviewed

**Verdict in 3 lines:** Four checkpoints, staged releases that tie to the A2.2 total, a kill rule with threshold, date and authority, and a failure family whose measure acts on the named risk. Two pieces of gate 2 evidence were due before their funding was released, and the month-7 hold and month-13 reading were not explained in the submitted text. All are fixed without changing your split, thresholds or owners.

**Rubric position (indicative, not a prediction):**

| Criterion | Before | After | Marks range (of 9) |
|---|---|---|---|
| 3-4 decision checkpoints with observable evidence | Full, with sequencing gaps | Full | - |
| Staged resources tied to gates | Full | Full | - |
| Actual kill rule | Full | Full | - |
| Failure-family treatment | Full | Full | 6-8 -> 7-9 (Estimate) |

## Changes made
| # | Where | Change | Rule / basis | Why it helps |
|---|---|---|---|---|
| 1 | Rows 2 and 3 | Gate 2 asked for "analysts trained" and "validation sign-off", but both are funded in gate 3, which is released only after gate 2. Now: reviewer named and training booked at gate 2; sign-off and training are conditions of go-live in gate 3. **The sign-off still precedes go-live, but now follows the gate 3 release** | Staged release; your 25 / 102 / 38 split kept | Removes a contradiction a marker could catch |
| 2 | Rows 1 and 2 | Inference projection moved from gate 1 (one pack) to gate 2 (3 packs), with "otherwise bucket 1 is revisited" | A2.2 and A2.3 test this on 3 pilot packs | Consistency with accepted sections |
| 3 | Row 3 | Month-7 hold now says what is held: "remaining gate 3 spend" | Partial descriptor: "not operational" | A hold now has a financial effect |
| 4 | Row 3 | Month 13 marked as past the 12-month costing horizon, which is unchanged. This was explained only in guide text, removed at compile | X-01 | Avoids an apparent horizon conflict |
| 5 | Row 1 | "Spike covers" -> "spike confirms every approved source is extractable" | Observable evidence; matches the failure measure | Pass or fail, not activity |
| 6 | Kill rule | Added year-1 benefit USD 40k and net (125) at 5 FTE (5 x 48 x 2/12; 40 - 165) | Honesty rule; was in guide text only | Shows the threshold's real economics |
| 7 | Failure measure | "USD 50k balance" -> "balance (USD 50k at Expected)"; labelled proposed control | The balance is 80 if bucket 6 reaches 90; rule 3 | Accurate across cases |
| 8 | Table 1 title, front matter, guide | Labelled gates as proposals with Ref E4, E7; removed guide blocks | Rule 3; compile hygiene | Clean, labelled text |

## Needs your input
- No [CONFIRM] items remain. Your confirmed values are in: 20 analyst-days at both gates, Head of Finance, Head of Business-HR.
- Please check edit 1. If you want the sign-off before the gate 3 money moves, the alternative is to shift about USD 3k from gate 3 to gate 2 (25 / 105 / 35). That is your call, so I did not make it.

## Judgement flags (not changed)
- **Sponsor independence (main flag):** the Head of Finance decides every gate, Finance is one of the two parties to the kill test, and the co-signer is a Finance manager. The sponsor can therefore pass their own test, and if that manager reports to the Head of Finance the co-sign is not independent. You also describe the sponsor as a heavy user of the packs, and the course warns about champion bias. This sits close to the A3 trap "the sponsor as sole owner of every call" and will be tested in B2 (independent challenge). A possible fix is to have the Head of Business-HR co-decide the kill test.
- **77% committed before binding evidence:** a gate 1 pass releases USD 102k on an in-principle agreement and one pack, so USD 127k of 165 is committed before the day-90 tests. If the binding agreement then fails at gate 2, only the last USD 38k is saved.
- **Gates limit the downside; they do not fix the case:** at 5 FTE the net is (125), Expected is (85) and probability-weighted about (74). A4 must address this directly.
- **Week 6 is tight:** a two-week spike and a pack of up to 20 analyst-days must both finish by then. You confirmed this timing.
- **Table 1 density:** the rows are close to a pilot plan, which rule 2 excludes. They are acceptable as gate evidence; trim first if the page count runs high.
- **Guide note wording:** your note says "six-month horizon". I read this as the 6-month reduction timeline, since the horizon stays 12 months (X-01).

## Checks
- **Arithmetic (recomputed): PASS.** 25 + 102 + 38 = 165; 15.2 / 61.8 / 23.0%; line items sum to each tranche and to each A2.2 bucket; reallocated 12 + 50 + 21 = 83; 132 and 195 at bucket 6 = 90; 5 FTE = USD 20k a month; 165 / 20 = 8.25 months, about month 19.
- **Consistency:** X-01 PASS (month 13 labelled); X-04 PASS for the A2.2 total, A4 tranche must equal USD 25k; X-11 PASS; X-17 PASS. X-05, X-07 and X-13 are N-A-yet: A4 or C4 must cite the kill rule; B2 must hold Executive sponsor, function Finance manager, Strategy & Analytics division lead, Head of Business-HR and the validation reviewer; C4's 90-day objective should span gates 1 and 2.
- **Timing:** go-live month 4 (E4), reductions months 5-10, saving from month 11 (A2.1, A2.3): PASS.
- **Word budget:** about 235 words outside Table 1, against 220 (+10% tolerance is 242).
- **Evidence:** E4 updated; no new E-ids.

## Next step
Edit v3 directly if you disagree, then run /prompt-accept A3.
