# CodeDriftBench Publishable Evidence Report

Profile: `smoke`
Run ID: `27484027705`
Observed slices: **4/4**
Observed observations: **4/4**
Mean executable score: **0.812**
95% bootstrap CI: **[0.812, 0.812]**
Baseline mean: **0.812**
Nonbaseline mean: **0.812**
Publishable evidence: **False**

## Gates
| Gate | Status |
|---|---:|
| complete_run | PASS |
| has_baseline | PASS |
| enough_nonbaseline_models | FAIL |
| enough_tasks | FAIL |
| enough_seeds | FAIL |
| enough_horizons | FAIL |
| strategy_ablation | FAIL |
| executable_scoring | PASS |
| reports_uncertainty | PASS |
| nontrivial_signal | FAIL |
| enough_observations | FAIL |

## Model summary
| Model | N | Mean | CI95 |
|---|---:|---:|---|
| baseline:copy | 2 | 0.812 | [0.812, 0.812] |
| qwen2.5-coder:1.5b | 2 | 0.812 | [0.812, 0.812] |

## Strategy summary
| Strategy | N | Mean | CI95 |
|---|---:|---:|---|
| no_anchor | 4 | 0.812 | [0.812, 0.812] |

## Claim card
Not publishable yet; see failed gates

This workflow uses executable AST/import/runtime checks, baselines, seeds, horizons, strategy ablations, bootstrap CIs, and explicit publishability gates.
