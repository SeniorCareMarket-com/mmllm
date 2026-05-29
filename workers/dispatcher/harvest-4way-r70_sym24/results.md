# harvest-4way-r70 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R70 ctrl_bpc |
|--------|--------|--------------:|
| T9IzT | origin/claude/train-sym24-711e81b6-T9IzT | 3.3157 |
| 7nGSy | fork-davidwuchn-mmllm-claude-train-sym24-f30e8296-7nGSy | 3.3762 |
| w3tUl | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-6c3f4b55-w3tUl | 3.4019 |
| gHf8k | fork-slaa-us-mmllm-claude-train-sym24-fb3eba04-gHf8k | 3.4339 |
| **mean** | | **3.3819** |
| **best** | | **3.3157** |

## Chain progression R68 → R70

Previous harvest: `workers/dispatcher/harvest-4way-r68_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3821         | 3.3819         | -0.0002 |
| ctrl_bpc best  | 3.2478         | 3.3157         | +0.0679 |

## Per-round trajectory (best bird: T9IzT)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 69 | 1189 | 3.3553 | +0.0100 |
| 70 | 1190 | 3.3157 | +0.0116 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **300 steps** from 15 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r68_sym24`

## Output

`workers/dispatcher/harvest-4way-r70_sym24/round-70/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

