# harvest-3way-r24 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R24 ctrl_bpc |
|--------|--------|--------------:|
| ROZ0O | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-b42923d3-ROZ0O | 3.8910 |
| 9IvbO | origin/claude/train-sym24-cc425730-9IvbO | 3.8993 |
| 2sYzL | fork-joly-os-mmllm-claude-train-sym24-5a11dd6b-2sYzL | 3.9000 |
| **mean** | | **3.8968** |
| **best** | | **3.8910** |

## Chain progression R22 → R24

Previous harvest: `workers/dispatcher/harvest-5way-r22_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.8971         | 3.8968         | -0.0003 |
| ctrl_bpc best  | 3.6670         | 3.8910         | +0.2240 |

## Per-round trajectory (best bird: ROZ0O)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 23 | 1208 | 3.8179 | +0.0115 |
| 24 | 1277 | 3.8910 | +0.0145 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **180 steps** from 11 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r22_sym24`

## Output

`workers/dispatcher/harvest-3way-r24_sym24/round-24/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

