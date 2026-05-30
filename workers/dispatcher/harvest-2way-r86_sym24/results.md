# harvest-2way-r86 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R86 ctrl_bpc |
|--------|--------|--------------:|
| n116z | fork-joly-os-mmllm-claude-train-sym24-434624fa-n116z | 3.3589 |
| IcZY2 | fork-SeniorCareMarket-mmllm-claude-train-sym24-2ebbf66c-IcZY2 | 3.4561 |
| **mean** | | **3.4075** |
| **best** | | **3.3589** |

## Per-round trajectory (best bird: n116z)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 85 | 1240 | 3.3633 | +0.0030 |
| 86 | 1237 | 3.3589 | +0.0138 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **40 steps** from 2 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r84_sym24`

## Output

`workers/dispatcher/harvest-2way-r86_sym24/round-86/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

