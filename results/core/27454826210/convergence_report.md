# CodeDriftBench Reproducible Evaluation Report

Run ID: `27454826210`  
Profile: `core`  
Complete run: `False` (98/180 slices)  

## Headline
- mean_CodeDriftScore: **0.7836390306122449**
- mean_SSR_final: **0.8205102040816327**
- mean_TestPassRate: **0.7887755102040817**
- mean_test_spec_gap: **-0.03173469387755102**
- test_spec_gap_CI95: **[-0.062482993197278916, -0.0012585034013605449]**
- mean_SSFR_any: **0.1336734693877551**
- mean_SSFR_critical: **0.1336734693877551**
- active_constraints_delta_SSR: **0.08864583333333334**
- active_constraints_delta_CI95: **[0.027708333333333342, 0.15083333333333335]**
- model_logparam_score_slope_mean: **-0.03790135001982307**
- mean_ConflictResistance: **0.7694132653061224**

## Publishability gates
- FAIL `complete_run`
- FAIL `enough_nonbaseline_models`
- PASS `has_baseline`
- PASS `enough_horizons`
- PASS `enough_seeds`
- PASS `enough_tasks`
- PASS `enough_task_slices`
- PASS `has_strategy_ablation`
- PASS `reports_uncertainty`
- PASS `controlled_decoding`
- PASS `has_model_metadata`
- PASS `has_dynamic_feature_tests`
- PASS `has_nontrivial_signal`

**Evidence grade:** 8.5/10 strong evidence package

## Claim discipline
- Safe claim: CodeDriftBench separately measures functional success, specification survival, and conflict resistance on real local model trajectories.
- Strong claim requires non-trivial effects with confidence intervals and a complete core/paper run.

## Leaderboard
| Rank | Model | ParamsB | Horizon | Strategy | Task | n | Score | SSR | SSFR_any | TestPass | CRS |
|---:|---|---:|---:|---|---|---:|---:|---:|---:|---:|---:|
| 1 | baseline:do_nothing | 0.0 | 10 | active_constraints | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 2 | baseline:do_nothing | 0.0 | 10 | active_constraints | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 3 | baseline:do_nothing | 0.0 | 10 | active_constraints | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 4 | baseline:do_nothing | 0.0 | 10 | active_constraints | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 5 | baseline:do_nothing | 0.0 | 10 | active_constraints | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 6 | baseline:do_nothing | 0.0 | 10 | no_anchor | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 7 | baseline:do_nothing | 0.0 | 10 | no_anchor | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 8 | baseline:do_nothing | 0.0 | 10 | no_anchor | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 9 | baseline:do_nothing | 0.0 | 10 | no_anchor | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 10 | baseline:do_nothing | 0.0 | 10 | no_anchor | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 11 | baseline:do_nothing | 0.0 | 10 | repeated_spec | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 12 | baseline:do_nothing | 0.0 | 10 | repeated_spec | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 13 | baseline:do_nothing | 0.0 | 10 | repeated_spec | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 14 | baseline:do_nothing | 0.0 | 10 | repeated_spec | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 15 | baseline:do_nothing | 0.0 | 10 | repeated_spec | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 16 | baseline:do_nothing | 0.0 | 25 | active_constraints | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 17 | baseline:do_nothing | 0.0 | 25 | active_constraints | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 18 | baseline:do_nothing | 0.0 | 25 | active_constraints | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 19 | baseline:do_nothing | 0.0 | 25 | active_constraints | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 20 | baseline:do_nothing | 0.0 | 25 | active_constraints | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 21 | baseline:do_nothing | 0.0 | 25 | no_anchor | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 22 | baseline:do_nothing | 0.0 | 25 | no_anchor | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 23 | baseline:do_nothing | 0.0 | 25 | no_anchor | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 24 | baseline:do_nothing | 0.0 | 25 | no_anchor | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 25 | baseline:do_nothing | 0.0 | 25 | no_anchor | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 26 | baseline:do_nothing | 0.0 | 25 | repeated_spec | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 27 | baseline:do_nothing | 0.0 | 25 | repeated_spec | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 28 | baseline:do_nothing | 0.0 | 25 | repeated_spec | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 29 | baseline:do_nothing | 0.0 | 25 | repeated_spec | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 30 | baseline:do_nothing | 0.0 | 25 | repeated_spec | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 31 | baseline:do_nothing | 0.0 | 50 | active_constraints | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 32 | baseline:do_nothing | 0.0 | 50 | active_constraints | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 33 | baseline:do_nothing | 0.0 | 50 | active_constraints | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 34 | baseline:do_nothing | 0.0 | 50 | active_constraints | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 35 | baseline:do_nothing | 0.0 | 50 | active_constraints | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 36 | baseline:do_nothing | 0.0 | 50 | no_anchor | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 37 | baseline:do_nothing | 0.0 | 50 | no_anchor | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 38 | baseline:do_nothing | 0.0 | 50 | no_anchor | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 39 | baseline:do_nothing | 0.0 | 50 | no_anchor | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 40 | baseline:do_nothing | 0.0 | 50 | no_anchor | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 41 | baseline:do_nothing | 0.0 | 50 | repeated_spec | config_parser | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 42 | baseline:do_nothing | 0.0 | 50 | repeated_spec | csv_schema | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 43 | baseline:do_nothing | 0.0 | 50 | repeated_spec | path_sanitizer | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 44 | baseline:do_nothing | 0.0 | 50 | repeated_spec | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 45 | baseline:do_nothing | 0.0 | 50 | repeated_spec | token_redactor | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 46 | qwen2.5-coder:0.5b | 0.5 | 10 | active_constraints | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 47 | qwen2.5-coder:0.5b | 0.5 | 10 | repeated_spec | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 48 | qwen2.5-coder:0.5b | 0.5 | 25 | active_constraints | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 49 | qwen2.5-coder:0.5b | 0.5 | 25 | repeated_spec | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 50 | qwen2.5-coder:0.5b | 0.5 | 50 | active_constraints | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 51 | qwen2.5-coder:0.5b | 0.5 | 50 | repeated_spec | todo_cli | 5 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 52 | qwen2.5-coder:1.5b | 1.5 | 10 | active_constraints | path_sanitizer | 2 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 53 | qwen2.5-coder:1.5b | 1.5 | 10 | no_anchor | token_redactor | 3 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 54 | qwen2.5-coder:1.5b | 1.5 | 10 | repeated_spec | path_sanitizer | 3 | 1.000 | 1.000 | 0.000 | 1.000 | 1.000 |
| 55 | qwen2.5-coder:1.5b | 1.5 | 10 | repeated_spec | token_redactor | 3 | 0.872 | 0.867 | 0.333 | 1.000 | 0.667 |
| 56 | qwen2.5-coder:1.5b | 1.5 | 10 | active_constraints | token_redactor | 2 | 0.853 | 0.800 | 0.500 | 1.000 | 0.750 |
| 57 | qwen2.5-coder:0.5b | 0.5 | 10 | repeated_spec | config_parser | 5 | 0.815 | 0.800 | 0.500 | 1.000 | 0.500 |
| 58 | qwen2.5-coder:0.5b | 0.5 | 10 | repeated_spec | token_redactor | 5 | 0.815 | 0.800 | 0.500 | 1.000 | 0.500 |
| 59 | qwen2.5-coder:0.5b | 0.5 | 25 | repeated_spec | config_parser | 5 | 0.809 | 0.800 | 0.600 | 1.000 | 0.500 |
| 60 | qwen2.5-coder:0.5b | 0.5 | 25 | repeated_spec | token_redactor | 5 | 0.809 | 0.800 | 0.600 | 1.000 | 0.500 |
| 61 | qwen2.5-coder:0.5b | 0.5 | 50 | repeated_spec | config_parser | 5 | 0.805 | 0.800 | 0.667 | 1.000 | 0.500 |
| 62 | qwen2.5-coder:0.5b | 0.5 | 50 | repeated_spec | token_redactor | 5 | 0.805 | 0.800 | 0.667 | 1.000 | 0.500 |
| 63 | qwen2.5-coder:0.5b | 0.5 | 10 | active_constraints | token_redactor | 5 | 0.785 | 0.800 | 1.000 | 1.000 | 0.500 |
| 64 | qwen2.5-coder:0.5b | 0.5 | 25 | active_constraints | token_redactor | 5 | 0.785 | 0.800 | 1.000 | 1.000 | 0.500 |
| 65 | qwen2.5-coder:0.5b | 0.5 | 50 | active_constraints | token_redactor | 5 | 0.785 | 0.800 | 1.000 | 1.000 | 0.500 |
| 66 | qwen2.5-coder:1.5b | 1.5 | 10 | repeated_spec | todo_cli | 3 | 0.667 | 0.667 | 0.500 | 1.000 | 0.000 |
| 67 | qwen2.5-coder:1.5b | 1.5 | 10 | no_anchor | path_sanitizer | 3 | 0.662 | 0.750 | 0.750 | 1.000 | 0.167 |
| 68 | qwen2.5-coder:0.5b | 0.5 | 50 | no_anchor | token_redactor | 5 | 0.610 | 0.600 | 0.667 | 0.833 | 0.500 |
| 69 | qwen2.5-coder:0.5b | 0.5 | 25 | no_anchor | token_redactor | 5 | 0.603 | 0.600 | 0.600 | 0.800 | 0.500 |
| 70 | qwen2.5-coder:0.5b | 0.5 | 10 | no_anchor | token_redactor | 5 | 0.593 | 0.600 | 0.500 | 0.750 | 0.500 |
| 71 | qwen2.5-coder:0.5b | 0.5 | 10 | active_constraints | config_parser | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 72 | qwen2.5-coder:0.5b | 0.5 | 10 | no_anchor | path_sanitizer | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 73 | qwen2.5-coder:0.5b | 0.5 | 10 | repeated_spec | path_sanitizer | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 74 | qwen2.5-coder:0.5b | 0.5 | 25 | active_constraints | config_parser | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 75 | qwen2.5-coder:0.5b | 0.5 | 25 | no_anchor | path_sanitizer | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 76 | qwen2.5-coder:0.5b | 0.5 | 25 | repeated_spec | path_sanitizer | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 77 | qwen2.5-coder:0.5b | 0.5 | 50 | active_constraints | config_parser | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 78 | qwen2.5-coder:0.5b | 0.5 | 50 | no_anchor | path_sanitizer | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 79 | qwen2.5-coder:0.5b | 0.5 | 50 | repeated_spec | path_sanitizer | 5 | 0.550 | 1.000 | 0.000 | 0.000 | 1.000 |
| 80 | qwen2.5-coder:0.5b | 0.5 | 10 | no_anchor | config_parser | 5 | 0.540 | 0.600 | 0.000 | 0.500 | 0.500 |
| 81 | qwen2.5-coder:1.5b | 1.5 | 10 | active_constraints | todo_cli | 2 | 0.517 | 0.417 | 0.375 | 0.875 | 0.000 |
| 82 | qwen2.5-coder:0.5b | 0.5 | 10 | active_constraints | csv_schema | 5 | 0.500 | 0.500 | 0.000 | 0.500 | 0.500 |
| 83 | qwen2.5-coder:0.5b | 0.5 | 10 | no_anchor | csv_schema | 5 | 0.500 | 0.500 | 0.000 | 0.500 | 0.500 |
| 84 | qwen2.5-coder:0.5b | 0.5 | 10 | repeated_spec | csv_schema | 5 | 0.500 | 0.500 | 0.000 | 0.500 | 0.500 |
| 85 | qwen2.5-coder:0.5b | 0.5 | 25 | no_anchor | config_parser | 5 | 0.495 | 0.600 | 0.000 | 0.400 | 0.500 |
| 86 | qwen2.5-coder:1.5b | 1.5 | 10 | active_constraints | config_parser | 2 | 0.490 | 0.400 | 0.250 | 0.750 | 0.250 |
| 87 | qwen2.5-coder:1.5b | 1.5 | 10 | no_anchor | todo_cli | 3 | 0.479 | 0.167 | 0.500 | 1.000 | 0.250 |
| 88 | qwen2.5-coder:0.5b | 0.5 | 50 | no_anchor | config_parser | 5 | 0.465 | 0.600 | 0.000 | 0.333 | 0.500 |
| 89 | qwen2.5-coder:0.5b | 0.5 | 25 | active_constraints | csv_schema | 5 | 0.455 | 0.500 | 0.000 | 0.400 | 0.500 |
| 90 | qwen2.5-coder:0.5b | 0.5 | 25 | repeated_spec | csv_schema | 5 | 0.455 | 0.500 | 0.000 | 0.400 | 0.500 |
| 91 | qwen2.5-coder:0.5b | 0.5 | 25 | no_anchor | csv_schema | 5 | 0.444 | 0.450 | 0.000 | 0.400 | 0.562 |
| 92 | qwen2.5-coder:0.5b | 0.5 | 50 | active_constraints | csv_schema | 5 | 0.427 | 0.500 | 0.000 | 0.333 | 0.515 |
| 93 | qwen2.5-coder:0.5b | 0.5 | 50 | repeated_spec | csv_schema | 5 | 0.427 | 0.500 | 0.000 | 0.333 | 0.515 |
| 94 | qwen2.5-coder:1.5b | 1.5 | 10 | no_anchor | config_parser | 3 | 0.385 | 0.400 | 0.000 | 0.500 | 0.000 |
| 95 | qwen2.5-coder:0.5b | 0.5 | 10 | active_constraints | path_sanitizer | 5 | 0.344 | 0.250 | 1.000 | 1.000 | 0.000 |
| 96 | qwen2.5-coder:0.5b | 0.5 | 25 | active_constraints | path_sanitizer | 5 | 0.340 | 0.250 | 1.000 | 1.000 | 0.000 |
| 97 | qwen2.5-coder:0.5b | 0.5 | 50 | active_constraints | path_sanitizer | 5 | 0.338 | 0.250 | 1.000 | 1.000 | 0.000 |
| 98 | qwen2.5-coder:0.5b | 0.5 | 50 | no_anchor | csv_schema | 5 | 0.335 | 0.250 | 0.000 | 0.333 | 0.570 |
| 99 | qwen2.5-coder:1.5b | 1.5 | 10 | repeated_spec | config_parser | 3 | 0.305 | 0.200 | 0.000 | 0.500 | 0.000 |
| 100 | qwen2.5-coder:0.5b | 0.5 | 10 | no_anchor | todo_cli | 5 | 0.262 | 0.000 | 0.000 | 0.500 | 0.250 |
| 101 | qwen2.5-coder:1.5b | 1.5 | 10 | no_anchor | csv_schema | 3 | 0.250 | 0.500 | 0.000 | 0.000 | 0.333 |
| 102 | qwen2.5-coder:0.5b | 0.5 | 25 | no_anchor | todo_cli | 5 | 0.195 | 0.000 | 0.000 | 0.400 | 0.100 |
| 103 | qwen2.5-coder:0.5b | 0.5 | 50 | no_anchor | todo_cli | 5 | 0.189 | 0.033 | 0.100 | 0.433 | 0.040 |
| 104 | qwen2.5-coder:1.5b | 1.5 | 10 | active_constraints | csv_schema | 2 | 0.100 | 0.250 | 0.000 | 0.000 | 0.000 |
| 105 | qwen2.5-coder:1.5b | 1.5 | 10 | repeated_spec | csv_schema | 3 | 0.100 | 0.250 | 0.000 | 0.000 | 0.000 |
