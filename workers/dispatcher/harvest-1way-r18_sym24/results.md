# harvest-1way-r18 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R18 ctrl_bpc |
|--------|--------|--------------:|
| zz865 | fork-SeniorCareMarket-mmllm-claude-train-sym24-e596b1c9-zz865 | 3.9300 |
| **mean** | | **3.9300** |
| **best** | | **3.9300** |

## Chain progression R17 → R18

Previous harvest: `workers/dispatcher/harvest-1way-r17_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 4.0250         | 3.9300         | -0.0950 |
| ctrl_bpc best  | 4.0250         | 3.9300         | -0.0950 |

## Per-round trajectory (best bird: zz865)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 17 | 1233 | 4.0250 | +0.0189 |
| 18 | 1260 | 3.9300 | +0.0113 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **100 steps** from 5 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r16_sym24`

## Output

`workers/dispatcher/harvest-1way-r18_sym24/round-18/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

