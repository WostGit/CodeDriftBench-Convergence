# CodeDriftBench Eight-Shard Bigger-Model Smoke Report

Run ID: `27483621046`
Complete: **True** (8/8 shards)
Missing shards: `none`
Mean score: **1.000**
Mean model duration: **25.0s**
Max model duration: **34s**

## Model summary
| Model | Shards | Mean score |
|---|---:|---:|
| qwen2.5-coder:1.5b | 4 | 1.000 |
| qwen2.5-coder:3b | 4 | 1.000 |

## Shards
| Case | Base case | Model | Duration | Return | Score |
|---|---|---|---:|---:|---:|
| config_timeout_1p5b | config_timeout | qwen2.5-coder:1.5b | 18s | 0 | 1.000 |
| config_timeout_3b | config_timeout | qwen2.5-coder:3b | 34s | 0 | 1.000 |
| redactor_aws_1p5b | redactor_aws | qwen2.5-coder:1.5b | 17s | 0 | 1.000 |
| redactor_aws_3b | redactor_aws | qwen2.5-coder:3b | 34s | 0 | 1.000 |
| todo_done_filter_1p5b | todo_done_filter | qwen2.5-coder:1.5b | 17s | 0 | 1.000 |
| todo_done_filter_3b | todo_done_filter | qwen2.5-coder:3b | 30s | 0 | 1.000 |
| todo_tags_1p5b | todo_tags | qwen2.5-coder:1.5b | 18s | 0 | 1.000 |
| todo_tags_3b | todo_tags | qwen2.5-coder:3b | 32s | 0 | 1.000 |

## Claim
Fast parallel bigger-model smoke probe only; not publishable benchmark evidence.
