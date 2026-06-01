# harvest-1way-r149 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R149 ctrl_bpc |
|--------|--------|--------------:|
| L08bc | origin/claude/train-sym24-f09da072-L08bc | 2.9449 |
| **mean** | | **2.9449** |
| **best** | | **2.9449** |

## Chain progression R140 → R149

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.9449         | +0.8939 |
| ctrl_bpc best  | 1.8188         | 2.9449         | +1.1261 |

## Per-round trajectory (best bird: L08bc)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 140 | — | 2.2669 | +0.5748 |
| 141 | — | 2.4027 | +0.5808 |
| 142 | — | 2.6632 | +0.2683 |
| 143 | — | 2.7447 | +0.2304 |
| 144 | — | 2.7460 | +0.3084 |
| 145 | — | 2.7079 | +0.3002 |
| 146 | — | 2.9750 | +0.2416 |
| 147 | — | 2.7269 | +0.2903 |
| 148 | — | 2.8910 | +0.2180 |
| 149 | — | 2.9449 | +0.1854 |

## Cumulative training contribution

- This harvest: **500 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **1170 steps** from 7 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r139_sym24`

## Output

`workers/dispatcher/harvest-1way-r149_sym24/round-149/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

