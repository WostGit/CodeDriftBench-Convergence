# CodeDriftBench Real-Model Convergence Report

Run ID: `27450157946`
Generated: `2026-06-13T00:21:20.737928+00:00`

## Headline

- mean_ConvergenceScore: **1.0000**
- mean_SSR_final: **1.0000**
- mean_SSFR: **0.0000**
- mean_TestPassRate: **1.0000**
- test_spec_gap: **0.0000**

A positive `test_spec_gap` means tests pass more often than durable constraints survive.

## Leaderboard

| Rank | Model | Horizon | Strategy | Score | SSR | CCS | SSFR | CHL | TestPass |
|---:|---|---:|---|---:|---:|---:|---:|---:|---:|
| 1 | qwen2.5-coder:0.5b | 5 | active_constraints | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 2 | qwen2.5-coder:1.5b | 5 | active_constraints | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 3 | qwen2.5-coder:0.5b | 5 | no_anchor | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 4 | qwen2.5-coder:1.5b | 5 | no_anchor | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |

## Convergence diagnostics

| Analysis | Model/Strategy | Horizon | Score slope | SSR slope | SSFR slope |
|---|---|---:|---:|---:|---:|
| model_order_convergence | active_constraints | 5 | 0.00000 | 0.00000 |  |
| model_order_convergence | no_anchor | 5 | 0.00000 | 0.00000 |  |
| horizon_degradation | qwen2.5-coder:0.5b / active_constraints |  | nan | nan | nan |
| horizon_degradation | qwen2.5-coder:0.5b / no_anchor |  | nan | nan | nan |
| horizon_degradation | qwen2.5-coder:1.5b / active_constraints |  | nan | nan | nan |
| horizon_degradation | qwen2.5-coder:1.5b / no_anchor |  | nan | nan | nan |
