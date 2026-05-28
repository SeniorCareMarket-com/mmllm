# harvest-4way-r36 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R36 ctrl_bpc |
|--------|--------|--------------:|
| o6uav | fork-joly-os-mmllm-claude-train-sym24-b40caaf4-o6uav | 3.5657 |
| atCN0 | origin/claude/train-sym24-0a41429b-atCN0 | 3.6261 |
| wSAVW | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-32bf8637-wSAVW | 3.6895 |
| ZIFUd | fork-slaa-us-mmllm-claude-train-sym24-c8db30bb-ZIFUd | 3.7487 |
| **mean** | | **3.6575** |
| **best** | | **3.5657** |

## Chain progression R34 → R36

Previous harvest: `workers/dispatcher/harvest-4way-r34_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.7141         | 3.6575         | -0.0566 |
| ctrl_bpc best  | 3.6673         | 3.5657         | -0.1016 |

## Per-round trajectory (best bird: o6uav)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 35 | 1278 | 3.6354 | +0.0150 |
| 36 | 1273 | 3.5657 | +0.0268 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r34_sym24`

## Output

`workers/dispatcher/harvest-4way-r36_sym24/round-36/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

