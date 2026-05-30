# harvest-1way-r108 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R108 ctrl_bpc |
|--------|--------|--------------:|
| x0Hrd | origin/claude/train-sym24-2cddaa2e-x0Hrd | 3.2429 |
| **mean** | | **3.2429** |
| **best** | | **3.2429** |

## Chain progression R106 → R108

Previous harvest: `workers/dispatcher/harvest-4way-r106_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2078         | 3.2429         | +0.0351 |
| ctrl_bpc best  | 3.1643         | 3.2429         | +0.0786 |

## Per-round trajectory (best bird: x0Hrd)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 107 | 1322 | 3.2137 | -0.0036 |
| 108 | 1282 | 3.2429 | -0.0001 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r106_sym24`

## Output

`workers/dispatcher/harvest-1way-r108_sym24/round-108/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

