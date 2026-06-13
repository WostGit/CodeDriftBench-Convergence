# CodeDriftBench Publishable Evidence Report

Run ID: `27452541458`  
Profile: `smoke`  
Generated: `2026-06-13T01:44:36.908799+00:00`

## Headline metrics

- mean_ConvergenceScore: **1.0**
- mean_SSR_final: **1.0**
- mean_SSFR: **0.0**
- mean_TestPassRate: **1.0**
- mean_test_spec_gap: **0.0**
- test_spec_gap_CI95: **[0.0, 0.0]**
- active_constraints_delta_SSR: **0.0**
- active_constraints_delta_CI95: **[0.0, 0.0]**
- repeated_spec_delta_SSR: **nan**
- model_order_score_slope_mean: **0.0**
- horizon_SSR_slope_mean: **nan**
- rank_reversal_rate: **0.0**

## Publishability gates

- FAIL `enough_models`
- FAIL `enough_horizons`
- FAIL `enough_seeds`
- PASS `enough_tasks`
- FAIL `enough_slices`
- PASS `has_strategy_ablation`
- PASS `reports_uncertainty`
- PASS `has_real_model_outputs`
- FAIL `has_nontrivial_signal`

**Evidence grade:** smoke-test only

## Claim card

- Safe claim: CodeDriftBench measures specification survival separately from functional test pass rate across real local model trajectories.
- Empirical claim allowed only if effect sizes are non-trivial: test pass rate and specification survival diverge over long horizons.
- Strong claim allowed only if confidence intervals exclude zero and rank reversals are observed.

## Leaderboard by task

| Rank | Model | Horizon | Strategy | Task | n | Score | SSR | CCS | SSFR | CHL | TestPass |
|---:|---|---:|---|---|---:|---:|---:|---:|---:|---:|---:|
| 1 | qwen2.5-coder:0.5b | 5 | active_constraints | config_parser | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 2 | qwen2.5-coder:0.5b | 5 | active_constraints | todo_cli | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 3 | qwen2.5-coder:0.5b | 5 | active_constraints | token_redactor | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 4 | qwen2.5-coder:0.5b | 5 | no_anchor | config_parser | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 5 | qwen2.5-coder:0.5b | 5 | no_anchor | todo_cli | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 6 | qwen2.5-coder:0.5b | 5 | no_anchor | token_redactor | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 7 | qwen2.5-coder:1.5b | 5 | active_constraints | config_parser | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 8 | qwen2.5-coder:1.5b | 5 | active_constraints | todo_cli | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 9 | qwen2.5-coder:1.5b | 5 | active_constraints | token_redactor | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 10 | qwen2.5-coder:1.5b | 5 | no_anchor | config_parser | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 11 | qwen2.5-coder:1.5b | 5 | no_anchor | todo_cli | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
| 12 | qwen2.5-coder:1.5b | 5 | no_anchor | token_redactor | 1 | 1.000 | 1.000 | 1.000 | 0.000 | 6.0 | 1.000 |
