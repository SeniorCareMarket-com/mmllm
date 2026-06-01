# harvest-3way-r123 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R123 ctrl_bpc |
|--------|--------|--------------:|
| NPQn3 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-0cefe106-NPQn3 | 2.8195 |
| 2bfXK | origin/claude/train-sym24-83d21546-2bfXK | 2.9624 |
| qFj4A | fork-slaa-us-mmllm-claude-train-sym24-8723069d-qFj4A | 2.9972 |
| **mean** | | **2.9264** |
| **best** | | **2.8195** |

## Chain progression R122 → R123

Previous harvest: `workers/dispatcher/harvest-5way-r122_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.8480         | 2.9264         | +0.0784 |
| ctrl_bpc best  | 2.7829         | 2.8195         | +0.0366 |

## Per-round trajectory (best bird: NPQn3)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 123 | 5475 | 2.8195 | +0.1178 |

## Cumulative training contribution

- This harvest: **150 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **500 steps** from 10 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r122_sym24`

## Output

`workers/dispatcher/harvest-3way-r123_sym24/round-123/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

