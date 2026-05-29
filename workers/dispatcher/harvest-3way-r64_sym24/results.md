# harvest-3way-r64 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R64 ctrl_bpc |
|--------|--------|--------------:|
| MQHib | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-3b5feb05-MQHib | 3.3330 |
| ZtHcR | fork-slaa-us-mmllm-claude-train-sym24-460295ea-ZtHcR | 3.4412 |
| Y6gch | origin/claude/train-sym24-557a0d43-Y6gch | 3.5195 |
| **mean** | | **3.4312** |
| **best** | | **3.3330** |

## Chain progression R62 → R64

Previous harvest: `workers/dispatcher/harvest-3way-r62_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4264         | 3.4312         | +0.0048 |
| ctrl_bpc best  | 3.3646         | 3.3330         | -0.0316 |

## Per-round trajectory (best bird: MQHib)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 63 | 1285 | 3.6087 | +0.0041 |
| 64 | 1236 | 3.3330 | +0.0201 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **260 steps** from 13 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r62_sym24`

## Output

`workers/dispatcher/harvest-3way-r64_sym24/round-64/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

