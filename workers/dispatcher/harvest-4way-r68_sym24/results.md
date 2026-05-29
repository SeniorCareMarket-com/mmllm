# harvest-4way-r68 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R68 ctrl_bpc |
|--------|--------|--------------:|
| xyG3w | fork-SeniorCareMarket-mmllm-claude-train-sym24-75811fe8-xyG3w | 3.2478 |
| yvWcJ | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-859d81fe-yvWcJ | 3.4147 |
| E1gU6 | fork-davidwuchn-mmllm-claude-train-sym24-6e7b4e0f-E1gU6 | 3.4279 |
| BPvSv | fork-slaa-us-mmllm-claude-train-sym24-78d16de2-BPvSv | 3.4378 |
| **mean** | | **3.3821** |
| **best** | | **3.2478** |

## Chain progression R66 → R68

Previous harvest: `workers/dispatcher/harvest-4way-r66_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2781         | 3.3821         | +0.1040 |
| ctrl_bpc best  | 3.2269         | 3.2478         | +0.0209 |

## Per-round trajectory (best bird: xyG3w)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 67 | 1270 | 3.2741 | +0.0190 |
| 68 | 1224 | 3.2478 | +0.0227 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r66_sym24`

## Output

`workers/dispatcher/harvest-4way-r68_sym24/round-68/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

