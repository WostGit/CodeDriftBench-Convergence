# CodeDriftBench Publishable Evidence Report

Profile: `core`
Run ID: `27485905583`
Observed slices: **72/72**
Observed observations: **216/216**
Mean legacy score: **0.984**
Mean feature score: **0.364**
Mean spec score: **0.735**
Silent spec failure rate: **0.486**
Baseline feature mean: **0.125**
Nonbaseline feature mean: **0.484**
Feature delta over baseline: **0.359**
Publishable evidence: **True**

## Gates
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
| enough_observations | PASS |
| separate_metrics_reported | PASS |

## Model feature summary
| Model | N | Mean feature | CI95 |
|---|---:|---:|---|
| baseline:copy | 72 | 0.125 | [0.076, 0.181] |
| qwen2.5-coder:1.5b | 72 | 0.208 | [0.148, 0.271] |
| qwen2.5-coder:3b | 72 | 0.759 | [0.662, 0.852] |

## Claim card
Publishable evidence package

Legacy, feature, and spec scores are separated. Publishability is gated on feature signal over the copy baseline, not on blended score.
