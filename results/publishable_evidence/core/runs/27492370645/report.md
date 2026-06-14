# CodeDriftBench Publishable Evidence Report

Profile: `core`
Run ID: `27492370645`
Observed slices: **72/72**
Observed observations: **216/216**
Mean legacy score: **0.984**
Mean feature score: **0.361**
Mean spec score: **0.734**
Silent spec failure rate: **0.486**
Strict feature pass rate: **0.264**
Legacy regression rate: **0.125**
Baseline feature mean: **0.125**
Nonbaseline feature mean: **0.479**
Feature delta over baseline: **0.354**
Mean baseline-adjusted feature lift: **0.354**
Baseline contamination rate: **0.250**
Core evidence package: **True**
Paper-grade evidence: **False**

## Core gates
| Gate | Status |
|---|---:|
| complete_run | PASS |
| has_baseline | PASS |
| enough_nonbaseline_models | PASS |
| enough_tasks | PASS |
| enough_seeds | PASS |
| enough_horizons | PASS |
| strategy_ablation | PASS |
| executable_scoring | PASS |
| reports_uncertainty | PASS |
| feature_signal_over_baseline | PASS |
| baseline_adjusted_lift_positive | PASS |
| enough_observations | PASS |
| separate_metrics_reported | PASS |
| model_ssfr_reported | PASS |
| task_summary_reported | PASS |
| strict_feature_pass_reported | PASS |
| legacy_regression_reported | PASS |
| baseline_contamination_audited | PASS |

## Paper-grade gates
| Gate | Status |
|---|---:|
| complete_run | PASS |
| has_baseline | PASS |
| enough_nonbaseline_models | PASS |
| enough_tasks | PASS |
| enough_seeds | PASS |
| enough_horizons | PASS |
| strategy_ablation | PASS |
| executable_scoring | PASS |
| reports_uncertainty | PASS |
| feature_signal_over_baseline | PASS |
| baseline_adjusted_lift_positive | PASS |
| enough_observations | PASS |
| separate_metrics_reported | PASS |
| model_ssfr_reported | PASS |
| task_summary_reported | PASS |
| strict_feature_pass_reported | PASS |
| legacy_regression_reported | PASS |
| baseline_contamination_audited | PASS |
| paper_profile | FAIL |
| paper_model_diversity | FAIL |
| paper_task_count | FAIL |
| paper_seed_count | FAIL |
| paper_strategy_count | FAIL |
| paper_observation_count | FAIL |
| baseline_contamination_below_20pct | FAIL |

## Model feature / SSFR summary
| Model | Feature mean | Strict pass | SSFR | Legacy regression |
|---|---:|---:|---:|---:|
| baseline:copy | 0.125 | 0.000 | 0.750 | 0.000 |
| qwen2.5-coder:1.5b | 0.208 | 0.042 | 0.708 | 0.000 |
| qwen2.5-coder:3b | 0.750 | 0.750 | 0.000 | 0.375 |

## Task summary
| Task | Feature mean | Spec mean | SSFR |
|---|---:|---:|---:|
| config_timeout | 0.667 | 0.858 | 0.000 |
| redactor_aws | 0.167 | 0.652 | 0.667 |
| todo_done_filter | 0.444 | 0.767 | 0.611 |
| todo_tags | 0.167 | 0.659 | 0.667 |

## Model x strategy feature summary
| Model | Strategy | Feature mean | CI95 |
|---|---|---:|---|
| baseline:copy | active_constraints | 0.125 | [0.056, 0.194] |
| baseline:copy | no_anchor | 0.125 | [0.056, 0.194] |
| qwen2.5-coder:1.5b | active_constraints | 0.236 | [0.139, 0.343] |
| qwen2.5-coder:1.5b | no_anchor | 0.181 | [0.111, 0.250] |
| qwen2.5-coder:3b | active_constraints | 0.500 | [0.333, 0.667] |
| qwen2.5-coder:3b | no_anchor | 1.000 | [1.000, 1.000] |

## Baseline contamination audit
Baseline feature contamination tasks: `config_timeout`

## Claim card
Core evidence package: passed reproducibility, separated-metric, baseline-adjusted, and signal gates. Paper-grade evidence still requires the paper profile and diversity gates.

This report separates legacy, feature, hygiene, and spec scores; reports strict pass rates, regression rates, SSFR by model/task/strategy, baseline-adjusted feature lift, and baseline contamination.
