# harvest-3way-r16 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R16 ctrl_bpc |
|--------|--------|--------------:|
| uEcSP | origin/claude/train-sym24-a028bfcd-uEcSP | 3.9761 |
| t8Cnu | fork-slaa-us-mmllm-claude-train-sym24-b88b7b83-t8Cnu | 4.1399 |
| 1X9fs | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-565f5e2e-1X9fs | 4.3741 |
| **mean** | | **4.1634** |
| **best** | | **3.9761** |

## Chain progression R14 → R16

Previous harvest: `workers/dispatcher/harvest-1way-r14_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 4.1615         | 4.1634         | +0.0019 |
| ctrl_bpc best  | 4.1615         | 3.9761         | -0.1854 |

## Per-round trajectory (best bird: uEcSP)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 15 | 972 | 4.0178 | +0.0182 |
| 16 | 946 | 3.9761 | +0.0235 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **140 steps** from 7 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r14_sym24`

## Output

`workers/dispatcher/harvest-3way-r16_sym24/round-16/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

