# harvest-1way-r237 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R237 ctrl_bpc |
|--------|--------|--------------:|
| lPmGh | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-0c45f7a0-lPmGh | 2.5502 |
| **mean** | | **2.5502** |
| **best** | | **2.5502** |

## Chain progression R236 → R237

Previous harvest: `workers/dispatcher/harvest-2way-r236_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.8076         | 2.5502         | -0.2574 |
| ctrl_bpc best  | 2.5540         | 2.5502         | -0.0038 |

## Per-round trajectory (best bird: lPmGh)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 237 | 3849 | 2.5502 | +0.0069 |

## Cumulative training contribution

- This harvest: **50 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **50 steps** from 1 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r236_sym24`

## Output

`workers/dispatcher/harvest-1way-r237_sym24/round-237/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

