# harvest-1way-r437 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R437 ctrl_bpc |
|--------|--------|--------------:|
| SKYyv | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-96dfa4cb-SKYyv | 2.2209 |
| **mean** | | **2.2209** |
| **best** | | **2.2209** |

## Chain progression R140 → R437

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.2209         | +0.1699 |
| ctrl_bpc best  | 1.8188         | 2.2209         | +0.4021 |

## Per-round trajectory (best bird: SKYyv)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 437 | 5378 | 2.2209 | +0.0156 |

## Cumulative training contribution

- This harvest: **50 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **50 steps** from 1 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r436_sym24`

## Output

`workers/dispatcher/harvest-1way-r437_sym24/round-437/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

