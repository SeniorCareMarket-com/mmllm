# harvest-2way-r127 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R127 ctrl_bpc |
|--------|--------|--------------:|
| guCvi | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-ce3e59cc-guCvi | 2.5683 |
| ME9D2 | fork-slaa-us-mmllm-claude-train-sym24-2fca7de1-ME9D2 | 2.6132 |
| **mean** | | **2.5907** |
| **best** | | **2.5683** |

## Chain progression R126 → R127

Previous harvest: `workers/dispatcher/harvest-3way-r126_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.6168         | 2.5907         | -0.0261 |
| ctrl_bpc best  | 2.5824         | 2.5683         | -0.0141 |

## Per-round trajectory (best bird: guCvi)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 127 | 5398 | 2.5683 | +0.1952 |

## Cumulative training contribution

- This harvest: **100 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **550 steps** from 11 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r126_sym24`

## Output

`workers/dispatcher/harvest-2way-r127_sym24/round-127/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

