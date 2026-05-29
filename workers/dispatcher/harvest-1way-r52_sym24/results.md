# harvest-1way-r52 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R52 ctrl_bpc |
|--------|--------|--------------:|
| FQmWs | fork-slaa-us-mmllm-claude-train-sym24-a7388409-FQmWs | 3.5746 |
| **mean** | | **3.5746** |
| **best** | | **3.5746** |

## Chain progression R50 → R52

Previous harvest: `workers/dispatcher/harvest-1way-r50_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.5756         | 3.5746         | -0.0010 |
| ctrl_bpc best  | 3.5756         | 3.5746         | -0.0010 |

## Per-round trajectory (best bird: FQmWs)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 51 | 1187 | 3.6182 | +0.0068 |
| 52 | 1217 | 3.5746 | +0.0145 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **100 steps** from 5 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r50_sym24`

## Output

`workers/dispatcher/harvest-1way-r52_sym24/round-52/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

