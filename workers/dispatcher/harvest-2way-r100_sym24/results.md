# harvest-2way-r100 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R100 ctrl_bpc |
|--------|--------|--------------:|
| Rl2jw | origin/claude/train-sym24-d850051c-Rl2jw | 3.2024 |
| lB7hE | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-087e1cff-lB7hE | 3.3195 |
| **mean** | | **3.2610** |
| **best** | | **3.2024** |

## Chain progression R98 → R100

Previous harvest: `workers/dispatcher/harvest-1way-r98_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.1848         | 3.2610         | +0.0762 |
| ctrl_bpc best  | 3.1848         | 3.2024         | +0.0176 |

## Per-round trajectory (best bird: Rl2jw)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 100 | 1233 | 3.2024 | +0.0453 |
| 99 | 1286 | 3.3669 | +0.0102 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **240 steps** from 12 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r98_sym24`

## Output

`workers/dispatcher/harvest-2way-r100_sym24/round-100/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

