# harvest-2way-r206 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R206 ctrl_bpc |
|--------|--------|--------------:|
| L08bc | origin/claude/train-sym24-67b8345b-L08bc | 2.8605 |
| L08bc | pr-106 | 2.8605 |
| **mean** | | **2.8605** |
| **best** | | **2.8605** |

## Chain progression R140 → R206

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.8605         | +0.8095 |
| ctrl_bpc best  | 1.8188         | 2.8605         | +1.0417 |

## Per-round trajectory (best bird: L08bc)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 199 | — | 2.9387 | -0.0197 |
| 200 | — | 2.8914 | -0.0010 |
| 201 | — | 2.8463 | -0.0042 |
| 202 | — | 2.8564 | +0.0051 |
| 203 | — | 2.8339 | -0.0256 |
| 204 | — | 2.8455 | -0.0179 |
| 205 | — | 2.8261 | +0.0103 |
| 206 | — | 2.8605 | -0.0265 |

## Cumulative training contribution

- This harvest: **400 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **400 steps** from 1 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r198_sym24`

## Output

`workers/dispatcher/harvest-2way-r206_sym24/round-206/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

