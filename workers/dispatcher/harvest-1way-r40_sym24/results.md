# harvest-1way-r40 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R40 ctrl_bpc |
|--------|--------|--------------:|
| U1krf | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-1c527f26-U1krf | 3.5559 |
| **mean** | | **3.5559** |
| **best** | | **3.5559** |

## Chain progression R38 → R40

Previous harvest: `workers/dispatcher/harvest-3way-r38_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.6067         | 3.5559         | -0.0508 |
| ctrl_bpc best  | 3.4963         | 3.5559         | +0.0596 |

## Per-round trajectory (best bird: U1krf)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 39 | 1298 | 3.4457 | +0.0162 |
| 40 | 1277 | 3.5559 | +0.0241 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **240 steps** from 12 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r38_sym24`

## Output

`workers/dispatcher/harvest-1way-r40_sym24/round-40/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

