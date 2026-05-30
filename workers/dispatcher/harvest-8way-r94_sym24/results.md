# harvest-8way-r94 — sparse-delta merge of 8 birds

## Worker endpoints

| handle | branch | R94 ctrl_bpc |
|--------|--------|--------------:|
| IvcC2 | fork-joly-os-mmllm-claude-train-sym24-bea27b17-IvcC2 | 3.0797 |
| KgNh3 | fork-SeniorCareMarket-mmllm-claude-train-sym24-ddaf01c1-KgNh3 | 3.2081 |
| wqptE | fork-slaa-us-mmllm-claude-train-sym24-89172b81-wqptE | 3.2198 |
| 0ZGip | fork-davidwuchn-mmllm-claude-train-sym24-f47a64e0-0ZGip | 3.2199 |
| nPXm5 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-06b7f71c-nPXm5 | 3.2418 |
| Q8Ca2 | origin/claude/train-sym24-1e0ac351-Q8Ca2 | 3.2735 |
| Z3dtw | fork-davidwuchn-mmllm-claude-train-sym24-346a3907-Z3dtw | 3.3224 |
| jMu2S | fork-joly-os-mmllm-claude-train-sym24-30740768-jMu2S | 3.3468 |
| **mean** | | **3.2390** |
| **best** | | **3.0797** |

## Per-round trajectory (best bird: IvcC2)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 93 | 1088 | 3.0596 | +0.0489 |
| 94 | 1063 | 3.0797 | +0.0353 |

## Cumulative training contribution

- This harvest: **160 steps** from 8 bird(s)
- Across full ancestry (deduped by bird_id): **160 steps** from 8 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r92_sym24`

## Output

`workers/dispatcher/harvest-8way-r94_sym24/round-94/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 8 workers)
- `dense.pt` (averaged across 8 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

