# harvest-1way-r159 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R159 ctrl_bpc |
|--------|--------|--------------:|
| L08bc | origin/claude/train-sym24-cfe04286-L08bc | 3.2407 |
| **mean** | | **3.2407** |
| **best** | | **3.2407** |

## Chain progression R149 → R159

Previous harvest: `workers/dispatcher/harvest-1way-r149_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.9449         | 3.2407         | +0.2958 |
| ctrl_bpc best  | 2.9449         | 3.2407         | +0.2958 |

## Per-round trajectory (best bird: L08bc)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 150 | — | 3.2649 | +0.0007 |
| 151 | — | 3.2691 | +0.0105 |
| 152 | — | 3.2439 | +0.0042 |
| 153 | — | 3.3046 | -0.0474 |
| 154 | — | 3.2275 | +0.0292 |
| 155 | — | 3.1887 | +0.0169 |
| 156 | — | 3.2475 | +0.0021 |
| 157 | — | 3.1981 | +0.0089 |
| 158 | — | 3.2182 | +0.0147 |
| 159 | — | 3.2407 | -0.0235 |

## Cumulative training contribution

- This harvest: **500 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **1500 steps** from 3 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r149_sym24`

## Output

`workers/dispatcher/harvest-1way-r159_sym24/round-159/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

