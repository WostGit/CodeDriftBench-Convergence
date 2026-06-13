# CodeDriftBench Reproducible Evaluation Report

Run ID: `27480458121`  
Profile: `smoke`  
Complete run: `True` (2/2 slices)  

## Headline
- mean_CodeDriftScore: **1.0**
- mean_SSR_final: **1.0**
- mean_TestPassRate: **1.0**
- mean_test_spec_gap: **0.0**
- test_spec_gap_CI95: **[0.0, 0.0]**
- mean_SSFR_any: **0.0**
- mean_SSFR_critical: **0.0**
- active_constraints_delta_SSR: **nan**
- active_constraints_delta_CI95: **[nan, nan]**
- model_logparam_score_slope_mean: **nan**
- mean_ConflictResistance: **1.0**

## Publishability gates
- PASS `complete_run`
- FAIL `enough_nonbaseline_models`
- PASS `has_baseline`
- FAIL `enough_horizons`
- FAIL `enough_seeds`
- FAIL `enough_tasks`
- FAIL `enough_task_slices`
- FAIL `has_strategy_ablation`
- PASS `reports_uncertainty`
- PASS `controlled_decoding`
- PASS `has_model_metadata`
- PASS `has_dynamic_feature_tests`
- FAIL `has_nontrivial_signal`

**Evidence grade:** smoke only

## Claim discipline
- Safe claim: CodeDriftBench separately measures functional success, specification survival, and conflict resistance on real local model trajectories.
- Strong claim requires non-trivial effects with confidence intervals and a complete core/paper run.

## Leaderboard
| Rank | Model | ParamsB | Horizon | Strategy | Task | n | Score | SSR | SSFR_any | TestPass | CRS |
|---:|---|---:|---:|---|---|---:|---:|---:|---:|---:|---:|
| 1 | baseline:do_nothing | 0.0 | 5 | active_constraints | todo_cli | 1 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 2 | qwen2.5-coder:0.5b | 0.5 | 5 | active_constraints | todo_cli | 1 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
