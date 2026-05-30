# harvest-1way-r82 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R82 ctrl_bpc |
|--------|--------|--------------:|
| fAl42 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-ada4d153-fAl42 | 3.4402 |
| **mean** | | **3.4402** |
| **best** | | **3.4402** |

## Chain progression R80 → R82

Previous harvest: `workers/dispatcher/harvest-2way-r80_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4693         | 3.4402         | -0.0291 |
| ctrl_bpc best  | 3.4086         | 3.4402         | +0.0316 |

## Per-round trajectory (best bird: fAl42)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 81 | 1240 | 3.4916 | +0.0002 |
| 82 | 1234 | 3.4402 | +0.0003 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **120 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r80_sym24`

## Output

`workers/dispatcher/harvest-1way-r82_sym24/round-82/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

