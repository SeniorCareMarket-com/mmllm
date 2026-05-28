# harvest-5way-r22 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R22 ctrl_bpc |
|--------|--------|--------------:|
| G8FtD | origin/claude/train-sym24-cc38c1e8-G8FtD | 3.6670 |
| 0sp7y | fork-SeniorCareMarket-mmllm-claude-train-sym24-9e4eba82-0sp7y | 3.8028 |
| sksfO | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-389014cb-sksfO | 3.9271 |
| AtfAd | fork-slaa-us-mmllm-claude-train-sym24-7fa250ba-AtfAd | 3.9329 |
| virsj | fork-joly-os-mmllm-claude-train-sym24-bb590220-virsj | 4.1559 |
| **mean** | | **3.8971** |
| **best** | | **3.6670** |

## Chain progression R20 → R22

Previous harvest: `workers/dispatcher/harvest-1way-r20_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 4.1839         | 3.8971         | -0.2868 |
| ctrl_bpc best  | 4.1839         | 3.6670         | -0.5169 |

## Per-round trajectory (best bird: G8FtD)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 21 | 1246 | 4.1689 | +0.0036 |
| 22 | 1272 | 3.6670 | +0.0059 |

## Cumulative training contribution

- This harvest: **100 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **140 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r20_sym24`

## Output

`workers/dispatcher/harvest-5way-r22_sym24/round-22/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

