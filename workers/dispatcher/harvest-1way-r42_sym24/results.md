# harvest-1way-r42 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R42 ctrl_bpc |
|--------|--------|--------------:|
| pKtiz | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-afd4f89b-pKtiz | 3.5969 |
| **mean** | | **3.5969** |
| **best** | | **3.5969** |

## Chain progression R40 → R42

Previous harvest: `workers/dispatcher/harvest-1way-r40_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.5559         | 3.5969         | +0.0410 |
| ctrl_bpc best  | 3.5559         | 3.5969         | +0.0410 |

## Per-round trajectory (best bird: pKtiz)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 41 | 1320 | 3.6536 | +0.0161 |
| 42 | 1196 | 3.5969 | +0.0109 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **180 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r40_sym24`

## Output

`workers/dispatcher/harvest-1way-r42_sym24/round-42/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

