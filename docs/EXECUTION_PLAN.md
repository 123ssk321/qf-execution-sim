# Execution Scenario Lab execution plan

Prepared 2026-10-25. **Queued; implementation inactive.** Original idea #9.

## Product contract

Compare declared execution schedules under explicit price, spread and impact assumptions. Model-implied shortfall is distinct from realized broker execution; the tool does not claim optimal live fills.

## Architecture and data

Seeded synthetic paths with known parameters. Public intraday volume may test forecast sensitivity only after license review. Minute bars cannot validate fills or permanent impact. Version inputs and generated seeds. Separate ingestion/generation, domain model, evaluation and public interface. First measure a bounded local run; paid data and cloud compute are outside this plan.

## Evaluation contract

Matched-risk baseline comparisons, derivation checks, forecast/impact misspecification sweeps, deterministic replay and unfavorable cases. Prespecify baselines, data splits and failure categories before final evaluation. Record exact commands, resource measurements, all tried variants and negative results. Simulated evidence remains separate from real-market or user validation.

## Milestones and hours

Months are relative to future activation. First public functional result: month 4; final decision: by month 9. One candidate uses the shared 16-hour weekly capacity, never six concurrent commitments. Total 312 hours includes 120 reserve.

| Milestone | Relative window | Task hours | Reserve | Cumulative |
| --- | --- | ---: | ---: | ---: |
| QE-M1: Scope and simulation contract | Months 1–2 | 32 | 20 | 52 |
| QE-M2: Baselines and path engine | Months 1–2 | 32 | 20 | 104 |
| QE-M3: First public comparison alpha | Month 4 | 32 | 20 | 156 |
| QE-M4: Impact and uncertainty tests | Months 5–7 | 32 | 20 | 208 |
| QE-M5: Usable research interface | Months 6–8 | 32 | 20 | 260 |
| QE-M6: Reproducible case study and decision | Months 7–9 | 32 | 20 | 312 |

## Public result and release gate

At milestone 3 publish a runnable artifact, generated or permitted inputs, correctness checks, a baseline, exact run instructions and an honest limitations report. This planning repository is not that artifact. A later stable release needs reproducible evaluation, failure evidence, bounded resource use and a named user workflow.

## Product decision

A scenario-analysis or educational tool is plausible; execution-desk value needs quotes, orders and real fill observations. If sophisticated schedules win only under their own calibrated assumptions, retain the simulator and negative findings rather than an optimization claim. At each milestone decide continue, narrow or park using actual hours and evidence. No recurring monitor, spending, live trading, conference submission or implementation is activated by this plan.
