# harvest-4way-r60 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R60 ctrl_bpc |
|--------|--------|--------------:|
| TzL87 | fork-joly-os-mmllm-claude-train-sym24-d3f1cad3-TzL87 | 3.3006 |
| hO0ZP | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-d91b08c6-hO0ZP | 3.4801 |
| uiH6e | fork-slaa-us-mmllm-claude-train-sym24-68dd1622-uiH6e | 3.5255 |
| 5JoOr | origin/claude/train-sym24-ae29cfda-5JoOr | 3.5305 |
| **mean** | | **3.4592** |
| **best** | | **3.3006** |

## Chain progression R58 → R60

Previous harvest: `workers/dispatcher/harvest-3way-r58_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4679         | 3.4592         | -0.0087 |
| ctrl_bpc best  | 3.4454         | 3.3006         | -0.1448 |

## Per-round trajectory (best bird: TzL87)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 59 | 1222 | 3.3081 | +0.0271 |
| 60 | 1264 | 3.3006 | +0.0280 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **300 steps** from 15 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r58_sym24`

## Output

`workers/dispatcher/harvest-4way-r60_sym24/round-60/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

