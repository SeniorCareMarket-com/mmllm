# harvest-1way-r110 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R110 ctrl_bpc |
|--------|--------|--------------:|
| 7PiXT | origin/claude/train-sym24-4168431f-7PiXT | 3.2727 |
| **mean** | | **3.2727** |
| **best** | | **3.2727** |

## Chain progression R108 → R110

Previous harvest: `workers/dispatcher/harvest-1way-r108_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2429         | 3.2727         | +0.0298 |
| ctrl_bpc best  | 3.2429         | 3.2727         | +0.0298 |

## Per-round trajectory (best bird: 7PiXT)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 109 | 1210 | 3.3246 | -0.0172 |
| 110 | 1341 | 3.2727 | -0.0002 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **220 steps** from 11 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r108_sym24`

## Output

`workers/dispatcher/harvest-1way-r110_sym24/round-110/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

