# harvest-1way-r76 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R76 ctrl_bpc |
|--------|--------|--------------:|
| fZoif | origin/claude/train-sym24-01df84a6-fZoif | 3.3570 |
| **mean** | | **3.3570** |
| **best** | | **3.3570** |

## Chain progression R74 → R76

Previous harvest: `workers/dispatcher/harvest-2way-r74_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3324         | 3.3570         | +0.0246 |
| ctrl_bpc best  | 3.3058         | 3.3570         | +0.0512 |

## Per-round trajectory (best bird: fZoif)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 75 | 1330 | 3.5273 | +0.0067 |
| 76 | 1330 | 3.3570 | +0.0126 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 10 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r74_sym24`

## Output

`workers/dispatcher/harvest-1way-r76_sym24/round-76/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

