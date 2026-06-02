# harvest-1way-r171 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R171 ctrl_bpc |
|--------|--------|--------------:|
| PA | origin/claude/train-sym24-14c7bd58-PA | 3.0154 |
| **mean** | | **3.0154** |
| **best** | | **3.0154** |

## Chain progression R169 → R171

Previous harvest: `workers/dispatcher/harvest-1way-r169_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.1179         | 3.0154         | -0.1025 |
| ctrl_bpc best  | 3.1179         | 3.0154         | -0.1025 |

## Per-round trajectory (best bird: PA)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 170 | — | 3.0489 | -0.0214 |
| 171 | — | 3.0154 | -0.0136 |

## Cumulative training contribution

- This harvest: **100 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **1600 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r169_sym24`

## Output

`workers/dispatcher/harvest-1way-r171_sym24/round-171/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

