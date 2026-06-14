# CodeDriftBench Executable Eight-Shard Smoke Report

Run ID: `27483824363`
Complete: **True** (8/8 shards)
Missing shards: `none`
Mean executable score: **0.984**
Failure count: **2**
Mean model duration: **25.0s**
Max model duration: **46s**

## Model summary
| Model | Shards | Mean executable score |
|---|---:|---:|
| qwen2.5-coder:1.5b | 4 | 0.969 |
| qwen2.5-coder:3b | 4 | 1.000 |

## Shards
| Case | Base case | Model | Duration | Return | Score | Failures |
|---|---|---|---:|---:|---:|---:|
| config_timeout_1p5b | config_timeout | qwen2.5-coder:1.5b | 14s | 0 | 0.938 | 1 |
| config_timeout_3b | config_timeout | qwen2.5-coder:3b | 30s | 0 | 1.000 | 0 |
| redactor_aws_1p5b | redactor_aws | qwen2.5-coder:1.5b | 17s | 0 | 1.000 | 0 |
| redactor_aws_3b | redactor_aws | qwen2.5-coder:3b | 33s | 0 | 1.000 | 0 |
| todo_done_filter_1p5b | todo_done_filter | qwen2.5-coder:1.5b | 16s | 0 | 0.938 | 1 |
| todo_done_filter_3b | todo_done_filter | qwen2.5-coder:3b | 46s | 0 | 1.000 | 0 |
| todo_tags_1p5b | todo_tags | qwen2.5-coder:1.5b | 16s | 0 | 1.000 | 0 |
| todo_tags_3b | todo_tags | qwen2.5-coder:3b | 28s | 0 | 1.000 | 0 |

## Claim
Executable smoke evidence only; score is based on AST/import/runtime behavior checks, not substring matching.
