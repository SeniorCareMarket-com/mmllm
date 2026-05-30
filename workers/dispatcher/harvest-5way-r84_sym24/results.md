# harvest-5way-r84 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R84 ctrl_bpc |
|--------|--------|--------------:|
| 9EdAD | origin/claude/train-sym24-3fff051a-9EdAD | 3.3186 |
| Zax9e | fork-joly-os-mmllm-claude-train-sym24-aa3fcf7f-Zax9e | 3.3656 |
| VVxXs | fork-SeniorCareMarket-mmllm-claude-train-sym24-11257c7e-VVxXs | 3.4075 |
| XTcvQ | fork-slaa-us-mmllm-claude-train-sym24-e0ac1743-XTcvQ | 3.4220 |
| zKiWS | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-6d740df8-zKiWS | 3.4632 |
| **mean** | | **3.3954** |
| **best** | | **3.3186** |

## Chain progression R82 → R84

Previous harvest: `workers/dispatcher/harvest-1way-r82_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4402         | 3.3954         | -0.0448 |
| ctrl_bpc best  | 3.4402         | 3.3186         | -0.1216 |

## Per-round trajectory (best bird: 9EdAD)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 83 | 978 | 3.3750 | +0.0193 |
| 84 | 1017 | 3.3186 | +0.0164 |

## Cumulative training contribution

- This harvest: **100 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 10 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r82_sym24`

## Output

`workers/dispatcher/harvest-5way-r84_sym24/round-84/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

