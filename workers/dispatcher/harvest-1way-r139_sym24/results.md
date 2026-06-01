# harvest-1way-r139 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R139 ctrl_bpc |
|--------|--------|--------------:|
| L08bc | origin/claude/train-sym24-8decca86-L08bc | 1.8188 |
| **mean** | | **1.8188** |
| **best** | | **1.8188** |

## Chain progression R129 → R139

Previous harvest: `workers/dispatcher/harvest-5way-r129_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.5707         | 1.8188         | -0.7519 |
| ctrl_bpc best  | 2.3107         | 1.8188         | -0.4919 |

## Per-round trajectory (best bird: L08bc)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 130 | — | 2.1860 | +0.1363 |
| 131 | — | 2.0918 | +0.2886 |
| 132 | — | 2.0092 | +0.4649 |
| 133 | — | 1.9725 | +0.6117 |
| 134 | — | 1.9420 | +0.5952 |
| 135 | — | 1.9139 | +0.6771 |
| 136 | — | 1.8797 | +0.6645 |
| 137 | — | 1.8615 | +0.7086 |
| 138 | — | 1.8327 | +0.7388 |
| 139 | — | 1.8188 | +0.8306 |

## Cumulative training contribution

- This harvest: **500 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **820 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r129_sym24`

## Output

`workers/dispatcher/harvest-1way-r139_sym24/round-139/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

