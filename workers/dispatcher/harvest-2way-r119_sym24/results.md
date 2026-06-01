# harvest-2way-r119 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R119 ctrl_bpc |
|--------|--------|--------------:|
| GRGdZ | fork-davidwuchn-mmllm-claude-train-sym24-a05f09d8-GRGdZ | 2.6234 |
| oPEy9 | fork-SeniorCareMarket-mmllm-claude-train-sym24-ee620cf0-oPEy9 | 2.9943 |
| **mean** | | **2.8089** |
| **best** | | **2.6234** |

## Per-round trajectory (best bird: GRGdZ)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 119 | 5856 | 2.6234 | +0.1226 |

## Cumulative training contribution

- This harvest: **100 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **100 steps** from 2 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r118_sym24`

## Output

`workers/dispatcher/harvest-2way-r119_sym24/round-119/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

