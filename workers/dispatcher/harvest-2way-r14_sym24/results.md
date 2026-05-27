# harvest-2way-r14 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R14 ctrl_bpc |
|--------|--------|--------------:|
| O0oGf | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-7568f590-O0oGf | 4.1615 |
| euElH | fork-SeniorCareMarket-mmllm-claude-train-sym24-7416f181-euElH | 4.2007 |
| **mean** | | **4.1811** |
| **best** | | **4.1615** |

## Per-round trajectory (best bird: O0oGf)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 13 | 1196 | 4.2328 | +0.0146 |
| 14 | 1249 | 4.1615 | +0.0129 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **40 steps** from 2 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r12_sym24`

## Output

`workers/dispatcher/harvest-2way-r14_sym24/round-14/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

