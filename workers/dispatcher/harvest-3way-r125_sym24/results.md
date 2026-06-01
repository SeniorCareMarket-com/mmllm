# harvest-3way-r125 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R125 ctrl_bpc |
|--------|--------|--------------:|
| QiK6R | origin/claude/train-sym24-c10ebc41-QiK6R | 2.4289 |
| OEumx | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-899ed081-OEumx | 2.6597 |
| ELjLL | fork-slaa-us-mmllm-claude-train-sym24-a690c05d-ELjLL | 2.7082 |
| **mean** | | **2.5989** |
| **best** | | **2.4289** |

## Chain progression R124 → R125

Previous harvest: `workers/dispatcher/harvest-3way-r124_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.6739         | 2.5989         | -0.0750 |
| ctrl_bpc best  | 2.5291         | 2.4289         | -0.1002 |

## Per-round trajectory (best bird: QiK6R)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 125 | 5706 | 2.4289 | +0.2458 |

## Cumulative training contribution

- This harvest: **150 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **700 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r124_sym24`

## Output

`workers/dispatcher/harvest-3way-r125_sym24/round-125/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

