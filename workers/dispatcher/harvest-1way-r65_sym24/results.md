# harvest-1way-r65 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R65 ctrl_bpc |
|--------|--------|--------------:|
| pmpFg | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-51ffe67f-pmpFg | 3.4226 |
| **mean** | | **3.4226** |
| **best** | | **3.4226** |

## Per-round trajectory (best bird: pmpFg)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 65 | 1366 | 3.4226 | +0.0143 |

## Cumulative training contribution

- This harvest: **10 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **10 steps** from 1 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r64_sym24`

## Output

`workers/dispatcher/harvest-1way-r65_sym24/round-65/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

