# harvest-2way-r78 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R78 ctrl_bpc |
|--------|--------|--------------:|
| ui5E3 | origin/claude/train-sym24-557cb327-ui5E3 | 3.3395 |
| F1k7r | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-cd1e6fba-F1k7r | 3.3970 |
| **mean** | | **3.3682** |
| **best** | | **3.3395** |

## Chain progression R76 → R78

Previous harvest: `workers/dispatcher/harvest-1way-r76_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3570         | 3.3682         | +0.0112 |
| ctrl_bpc best  | 3.3570         | 3.3395         | -0.0175 |

## Per-round trajectory (best bird: ui5E3)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 77 | 1387 | 3.4162 | -0.0068 |
| 78 | 1244 | 3.3395 | +0.0141 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **160 steps** from 8 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r76_sym24`

## Output

`workers/dispatcher/harvest-2way-r78_sym24/round-78/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

