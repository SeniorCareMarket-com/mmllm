# harvest-1way-r17 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R17 ctrl_bpc |
|--------|--------|--------------:|
| zz865 | fork-SeniorCareMarket-mmllm-claude-train-sym24-e596b1c9-zz865 | 4.0250 |
| **mean** | | **4.0250** |
| **best** | | **4.0250** |

## Chain progression R16 → R17

Previous harvest: `workers/dispatcher/harvest-3way-r16_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 4.1634         | 4.0250         | -0.1384 |
| ctrl_bpc best  | 3.9761         | 4.0250         | +0.0489 |

## Per-round trajectory (best bird: zz865)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 17 | 1233 | 4.0250 | +0.0189 |

## Cumulative training contribution

- This harvest: **10 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **110 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r16_sym24`

## Output

`workers/dispatcher/harvest-1way-r17_sym24/round-17/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

