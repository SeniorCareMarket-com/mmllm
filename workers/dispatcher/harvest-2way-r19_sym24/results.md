# harvest-2way-r19 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R19 ctrl_bpc |
|--------|--------|--------------:|
| pushverify | origin/claude/train-sym24-01b6774e-pushverify | 4.1359 |
| pushfix-test | origin/claude/train-sym24-b6a5a35f-pushfix-test | 4.1567 |
| **mean** | | **4.1463** |
| **best** | | **4.1359** |

## Chain progression R18 → R19

Previous harvest: `workers/dispatcher/harvest-1way-r18_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.9300         | 4.1463         | +0.2163 |
| ctrl_bpc best  | 3.9300         | 4.1359         | +0.2059 |

## Per-round trajectory (best bird: pushverify)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 19 | 710 | 4.1359 | +0.0200 |

## Cumulative training contribution

- This harvest: **10 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **90 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r18_sym24`

## Output

`workers/dispatcher/harvest-2way-r19_sym24/round-19/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

