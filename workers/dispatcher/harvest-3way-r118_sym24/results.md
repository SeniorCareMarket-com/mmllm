# harvest-3way-r118 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R118 ctrl_bpc |
|--------|--------|--------------:|
| yDfBT | fork-slaa-us-mmllm-claude-train-sym24-d2cf3ab0-yDfBT | 2.6205 |
| WN1st | fork-SeniorCareMarket-mmllm-claude-train-sym24-1fba61ce-WN1st | 2.6739 |
| iYemo | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-14f52e6d-iYemo | 2.9587 |
| **mean** | | **2.7510** |
| **best** | | **2.6205** |

## Per-round trajectory (best bird: yDfBT)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 118 | 5554 | 2.6205 | +0.0890 |

## Cumulative training contribution

- This harvest: **150 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **150 steps** from 3 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r117_sym24`

## Output

`workers/dispatcher/harvest-3way-r118_sym24/round-118/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

