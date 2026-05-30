# harvest-5way-r98 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R98 ctrl_bpc |
|--------|--------|--------------:|
| AuYFj | fork-SeniorCareMarket-mmllm-claude-train-sym24-cd751481-AuYFj | 3.1718 |
| Zx45N | origin/claude/train-sym24-cdea96e5-Zx45N | 3.1848 |
| RZEmH | fork-slaa-us-mmllm-claude-train-sym24-b0791940-RZEmH | 3.2970 |
| LDmQL | fork-joly-os-mmllm-claude-train-sym24-6ca0cc4e-LDmQL | 3.3155 |
| AFYJk | fork-davidwuchn-mmllm-claude-train-sym24-567c992a-AFYJk | 3.3419 |
| **mean** | | **3.2622** |
| **best** | | **3.1718** |

## Per-round trajectory (best bird: AuYFj)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 97 | 1308 | 3.1477 | +0.0377 |
| 98 | 1217 | 3.1718 | +0.0388 |

## Cumulative training contribution

- This harvest: **100 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **100 steps** from 5 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r96_sym24`

## Output

`workers/dispatcher/harvest-5way-r98_sym24/round-98/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

