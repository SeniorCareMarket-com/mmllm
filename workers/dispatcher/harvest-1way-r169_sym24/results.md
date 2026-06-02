# harvest-1way-r169 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R169 ctrl_bpc |
|--------|--------|--------------:|
| L08bc | origin/claude/train-sym24-0945cb27-L08bc | 3.1179 |
| **mean** | | **3.1179** |
| **best** | | **3.1179** |

## Chain progression R159 → R169

Previous harvest: `workers/dispatcher/harvest-1way-r159_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2407         | 3.1179         | -0.1228 |
| ctrl_bpc best  | 3.2407         | 3.1179         | -0.1228 |

## Per-round trajectory (best bird: L08bc)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 160 | — | 3.1611 | +0.0018 |
| 161 | — | 3.1839 | -0.0261 |
| 162 | — | 3.1617 | -0.0208 |
| 163 | — | 3.1689 | -0.0134 |
| 164 | — | 3.1651 | +0.0367 |
| 165 | — | 3.1647 | -0.0088 |
| 166 | — | 3.1510 | +0.0138 |
| 167 | — | 3.1908 | -0.0142 |
| 168 | — | 3.2013 | -0.0213 |
| 169 | — | 3.1179 | -0.0276 |

## Cumulative training contribution

- This harvest: **500 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **2000 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r159_sym24`

## Output

`workers/dispatcher/harvest-1way-r169_sym24/round-169/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

