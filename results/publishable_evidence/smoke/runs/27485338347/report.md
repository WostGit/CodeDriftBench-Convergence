# CodeDriftBench Publishable Evidence Report

Profile: `smoke`
Run ID: `27485338347`
Observed slices: **4/4**
Observed observations: **12/12**
Mean legacy score: **1.000**
Mean feature score: **0.056**
Mean spec score: **0.622**
Silent spec failure rate: **1.000**
Baseline feature mean: **0.000**
Nonbaseline feature mean: **0.111**
Feature delta over baseline: **0.111**
Publishable evidence: **False**

## Gates
| Gate | Status |
|---|---:|
| complete_run | PASS |
| has_baseline | PASS |
| enough_nonbaseline_models | FAIL |
| enough_tasks | FAIL |
| enough_seeds | FAIL |
| enough_horizons | PASS |
| strategy_ablation | FAIL |
| executable_scoring | PASS |
| reports_uncertainty | PASS |
| feature_signal_over_baseline | PASS |
| enough_observations | FAIL |
| separate_metrics_reported | PASS |

## Model feature summary
| Model | N | Mean feature | CI95 |
|---|---:|---:|---|
| baseline:copy | 6 | 0.000 | [0.000, 0.000] |
| qwen2.5-coder:1.5b | 6 | 0.111 | [0.000, 0.222] |

## Claim card
Not publishable yet; see failed gates

Legacy, feature, and spec scores are separated. Publishability is gated on feature signal over the copy baseline, not on blended score.
