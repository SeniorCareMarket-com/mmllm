# harvest-1way-r48 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R48 ctrl_bpc |
|--------|--------|--------------:|
| qpwy6 | origin/claude/train-sym24-af45fdd2-qpwy6 | 3.5859 |
| **mean** | | **3.5859** |
| **best** | | **3.5859** |

## Chain progression R46 → R48

Previous harvest: `workers/dispatcher/harvest-2way-r46_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4323         | 3.5859         | +0.1536 |
| ctrl_bpc best  | 3.3206         | 3.5859         | +0.2653 |

## Per-round trajectory (best bird: qpwy6)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 47 | 1020 | 3.5949 | +0.0138 |
| 48 | 1038 | 3.5859 | +0.0165 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **120 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r46_sym24`

## Output

`workers/dispatcher/harvest-1way-r48_sym24/round-48/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

