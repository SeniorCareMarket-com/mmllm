# harvest-3way-r173 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R173 ctrl_bpc |
|--------|--------|--------------:|
| P3 | origin/claude/train-sym24-3b7e6b28-P3 | 3.0608 |
| P1 | origin/claude/train-sym24-6a6a3e6b-P1 | 3.4706 |
| P2 | origin/claude/train-sym24-50f8a9c8-P2 | 3.6704 |
| **mean** | | **3.4006** |
| **best** | | **3.0608** |

## Chain progression R171 → R173

Previous harvest: `workers/dispatcher/harvest-1way-r171_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.0154         | 3.4006         | +0.3852 |
| ctrl_bpc best  | 3.0154         | 3.0608         | +0.0454 |

## Per-round trajectory (best bird: P3)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 172 | — | 3.0055 | -0.0081 |
| 173 | — | 3.0608 | -0.0293 |

## Cumulative training contribution

- This harvest: **300 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **1400 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r171_sym24`

## Output

`workers/dispatcher/harvest-3way-r173_sym24/round-173/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

