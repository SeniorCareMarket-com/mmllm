# harvest-1way-r20 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R20 ctrl_bpc |
|--------|--------|--------------:|
| smoke2 | origin/claude/train-sym24-db816315-smoke2 | 4.1839 |
| **mean** | | **4.1839** |
| **best** | | **4.1839** |

## Chain progression R19 → R20

Previous harvest: `workers/dispatcher/harvest-2way-r19_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 4.1463         | 4.1839         | +0.0376 |
| ctrl_bpc best  | 4.1359         | 4.1839         | +0.0480 |

## Per-round trajectory (best bird: smoke2)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 20 | 1040 | 4.1839 | +0.0116 |

## Cumulative training contribution

- This harvest: **10 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **40 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r19_sym24`

## Output

`workers/dispatcher/harvest-1way-r20_sym24/round-20/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

