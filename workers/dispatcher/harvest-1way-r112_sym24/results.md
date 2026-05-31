# harvest-1way-r112 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R112 ctrl_bpc |
|--------|--------|--------------:|
| JhqsP | origin/claude/train-sym24-ccbff613-JhqsP | 3.1699 |
| **mean** | | **3.1699** |
| **best** | | **3.1699** |

## Chain progression R110 → R112

Previous harvest: `workers/dispatcher/harvest-1way-r110_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2727         | 3.1699         | -0.1028 |
| ctrl_bpc best  | 3.2727         | 3.1699         | -0.1028 |

## Per-round trajectory (best bird: JhqsP)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 111 | 1220 | 3.2460 | +0.0178 |
| 112 | 1164 | 3.1699 | +0.0010 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **140 steps** from 7 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r110_sym24`

## Output

`workers/dispatcher/harvest-1way-r112_sym24/round-112/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

