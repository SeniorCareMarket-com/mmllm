# harvest-4way-r26 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R26 ctrl_bpc |
|--------|--------|--------------:|
| lKcgO | fork-joly-os-mmllm-claude-train-sym24-d667ba68-lKcgO | 3.5302 |
| 3r69k | origin/claude/train-sym24-ffbcb463-3r69k | 3.5556 |
| wyl9h | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-2a983f02-wyl9h | 3.8617 |
| Ux4aW | fork-slaa-us-mmllm-claude-train-sym24-a9c17954-Ux4aW | 3.8869 |
| **mean** | | **3.7086** |
| **best** | | **3.5302** |

## Chain progression R24 → R26

Previous harvest: `workers/dispatcher/harvest-3way-r24_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.8968         | 3.7086         | -0.1882 |
| ctrl_bpc best  | 3.8910         | 3.5302         | -0.3608 |

## Per-round trajectory (best bird: lKcgO)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 25 | 1199 | 3.6569 | +0.0082 |
| 26 | 1225 | 3.5302 | +0.0052 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **250 steps** from 13 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r24_sym24`

## Output

`workers/dispatcher/harvest-4way-r26_sym24/round-26/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

