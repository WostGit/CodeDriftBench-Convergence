# CodeDriftBench Methods

This single workflow is the benchmark artifact. It evaluates whether specification drift converges, plateaus, or compounds across repeated executable code edits.

## Scores
- legacy_score: old API/behavior preservation
- feature_score: newly requested behavior survival
- hygiene_score: parse/import/dependency hygiene
- spec_score: 0.25*hygiene + 0.35*legacy + 0.40*feature
- silent_spec_failure: legacy_score >= 0.90 and feature_score < 0.50

## Convergence classes
- stable_success: late legacy and feature are both high
- silent_plateau: late legacy high, late feature low, SSFR true
- regression_tradeoff: feature improves while legacy declines
- compounding_drift: both feature and legacy decline
- unstable: large step-to-step spec swing
- partial_or_flat: no stronger class applies

## Validity gates
Runs always emit debug artifacts. Strong claims require complete slices/observations, low infrastructure failure, low parse failure, baseline contamination audits, and trajectory metrics.
