# harvest-1way-r128 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R128 ctrl_bpc |
|--------|--------|--------------:|
| 6AjUu | fork-slaa-us-mmllm-claude-train-sym24-e0643374-6AjUu | 2.6767 |
| **mean** | | **2.6767** |
| **best** | | **2.6767** |

## Chain progression R127 → R128

Previous harvest: `workers/dispatcher/harvest-2way-r127_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.5907         | 2.6767         | +0.0860 |
| ctrl_bpc best  | 2.5683         | 2.6767         | +0.1084 |

## Per-round trajectory (best bird: 6AjUu)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 128 | 5377 | 2.6767 | +0.1984 |

## Cumulative training contribution

- This harvest: **50 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **450 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r127_sym24`

## Output

`workers/dispatcher/harvest-1way-r128_sym24/round-128/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

