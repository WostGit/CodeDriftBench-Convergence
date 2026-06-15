# CodeDriftBench Publishable Evidence Report

Profile: `core`
Run ID: `27516502838`
Research question: **Does specification drift converge, plateau, or compound across repeated code edits?**
Observed slices: **72/72**
Observed observations: **216/216**
Mean legacy score: **0.986**
Mean feature score: **0.276**
Mean spec score: **0.701**
Silent spec failure rate: **0.653**
SSFR excluding infra failures: **0.667**
Strict feature pass rate: **0.259**
Legacy regression rate: **0.125**
Baseline feature mean: **0.000**
Nonbaseline feature mean: **0.414**
Feature delta over baseline: **0.414**
Mean baseline-adjusted feature lift: **0.414**
Baseline contamination rate: **0.000**
Model-call failure rate: **0.013**
Parse failure rate: **0.000**
Fallback-to-previous-code rate: **0.013**
Core evidence package: **True**
Paper-grade evidence: **False**

## Claim card
Core convergence evidence package: passed reproducibility, separated-metric, trajectory, infrastructure, baseline-adjusted, and signal gates. Paper-grade evidence still requires the paper profile and diversity gates.

## Convergence class summary
| Class | n | rate |
|---|---:|---:|
| partial_or_flat | 9 | 0.125 |
| silent_plateau | 45 | 0.625 |
| stable_success | 18 | 0.250 |

## Horizon summary
| Horizon | Feature mean | Legacy mean | Spec mean | SSFR | Infra clean |
|---:|---:|---:|---:|---:|---:|
| 10 | 0.273 | 0.986 | 0.701 | 0.667 | 0.972 |
| 20 | 0.306 | 0.986 | 0.711 | 0.625 | 0.958 |
| 5 | 0.250 | 0.986 | 0.692 | 0.667 | 0.986 |

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
| trajectory_metrics_reported | PASS |
| convergence_classes_reported | PASS |
| horizon_summary_reported | PASS |
| infra_failure_rate_below_2pct | PASS |
| parse_failure_rate_below_2pct | PASS |
| fallback_rate_reported | PASS |
| baseline_contamination_below_10pct | PASS |
| nonbaseline_failure_examples_present | PASS |

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
| trajectory_metrics_reported | PASS |
| convergence_classes_reported | PASS |
| horizon_summary_reported | PASS |
| infra_failure_rate_below_2pct | PASS |
| parse_failure_rate_below_2pct | PASS |
| fallback_rate_reported | PASS |
| baseline_contamination_below_10pct | PASS |
| nonbaseline_failure_examples_present | PASS |
| paper_profile | FAIL |
| paper_model_diversity | FAIL |
| paper_task_count | FAIL |
| paper_seed_count | FAIL |
| paper_strategy_count | FAIL |
| paper_observation_count | FAIL |
| baseline_contamination_below_20pct | PASS |

## Baseline contamination audit
Baseline feature contamination tasks: `none`

## Debug artifacts
- `debug_summary.md`
- `slice_manifest.csv`
- `raw_errors.json`
- `trajectory_metrics.csv`
- `methods.md`
