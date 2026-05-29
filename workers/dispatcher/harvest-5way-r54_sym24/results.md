# harvest-5way-r54 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R54 ctrl_bpc |
|--------|--------|--------------:|
| DOr2v | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-74558133-DOr2v | 3.5621 |
| ARwNM | fork-slaa-us-mmllm-claude-train-sym24-5abb68db-ARwNM | 3.5753 |
| DLJiM | fork-joly-os-mmllm-claude-train-sym24-6cd32ac5-DLJiM | 3.6102 |
| cDTUo | origin/claude/train-sym24-4b48e702-cDTUo | 3.6162 |
| lt4P8 | fork-SeniorCareMarket-mmllm-claude-train-sym24-ed662fb4-lt4P8 | 3.6800 |
| **mean** | | **3.6088** |
| **best** | | **3.5621** |

## Chain progression R52 → R54

Previous harvest: `workers/dispatcher/harvest-1way-r52_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.5746         | 3.6088         | +0.0342 |
| ctrl_bpc best  | 3.5746         | 3.5621         | -0.0125 |

## Per-round trajectory (best bird: DOr2v)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 53 | 1202 | 3.6574 | +0.0133 |
| 54 | 1182 | 3.5621 | +0.0158 |

## Cumulative training contribution

- This harvest: **100 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **160 steps** from 8 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r52_sym24`

## Output

`workers/dispatcher/harvest-5way-r54_sym24/round-54/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

