# Research brief

Source idea: #9 in the original ten-idea document. Revised ranking: quick.

## Product and evidence boundary

Compare declared execution schedules under explicit price, spread and impact assumptions. Model-implied shortfall is distinct from realized broker execution; the tool does not claim optimal live fills.

## Data path

Seeded synthetic paths with known parameters. Public intraday volume may test forecast sensitivity only after license review. Minute bars cannot validate fills or permanent impact.

## Research evidence

Matched-risk baseline comparisons, derivation checks, forecast/impact misspecification sweeps, deterministic replay and unfavorable cases.

## Product hypothesis and stop rule

A scenario-analysis or educational tool is plausible; execution-desk value needs quotes, orders and real fill observations. If sophisticated schedules win only under their own calibrated assumptions, retain the simulator and negative findings rather than an optimization claim.

## Source link and evidence caution

The [Almgren–Chriss model paper](https://doi.org/10.21314/JOR.2001.041) provides the execution model foundation. Simulated paths and public volume data can test assumptions and sensitivity; neither validates broker fills or permanent impact.

Planning assessment: 19 October 2026.
