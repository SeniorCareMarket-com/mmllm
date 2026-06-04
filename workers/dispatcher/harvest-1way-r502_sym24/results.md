# harvest-1way-r502 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R502 ctrl_bpc |
|--------|--------|--------------:|
| ZuQMS | fork-slaa-us-mmllm-claude-train-sym24-b4bbcd49-ZuQMS | 2.6507 |
| **mean** | | **2.6507** |
| **best** | | **2.6507** |

## Chain progression R140 → R502

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.6507         | +0.5997 |
| ctrl_bpc best  | 1.8188         | 2.6507         | +0.8319 |

## Per-round trajectory (best bird: ZuQMS)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 502 | 4134 | 2.6507 | +0.0156 |

## Cumulative training contribution

- This harvest: **50 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **50 steps** from 1 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r501_sym24`

## Output

`workers/dispatcher/harvest-1way-r502_sym24/round-502/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

