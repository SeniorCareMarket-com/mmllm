# harvest-1way-r362 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R362 ctrl_bpc |
|--------|--------|--------------:|
| seqAn | fork-slaa-us-mmllm-claude-train-sym24-ca327229-seqAn | 2.2602 |
| **mean** | | **2.2602** |
| **best** | | **2.2602** |

## Chain progression R140 → R362

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.2602         | +0.2092 |
| ctrl_bpc best  | 1.8188         | 2.2602         | +0.4414 |

## Per-round trajectory (best bird: seqAn)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 362 | 5344 | 2.2602 | +0.0114 |

## Cumulative training contribution

- This harvest: **50 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **50 steps** from 1 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r361_sym24`

## Output

`workers/dispatcher/harvest-1way-r362_sym24/round-362/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

