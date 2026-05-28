# harvest-2way-r30 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R30 ctrl_bpc |
|--------|--------|--------------:|
| 33fdo | fork-joly-os-mmllm-claude-train-sym24-f2250e52-33fdo | 3.6637 |
| tzzqE | origin/claude/train-sym24-6f6ab487-tzzqE | 3.7718 |
| **mean** | | **3.7177** |
| **best** | | **3.6637** |

## Chain progression R28 → R30

Previous harvest: `workers/dispatcher/harvest-4way-r28_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.7541         | 3.7177         | -0.0364 |
| ctrl_bpc best  | 3.7014         | 3.6637         | -0.0377 |

## Per-round trajectory (best bird: 33fdo)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 29 | 1212 | 3.8786 | +0.0112 |
| 30 | 1207 | 3.6637 | +0.0097 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **260 steps** from 13 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r28_sym24`

## Output

`workers/dispatcher/harvest-2way-r30_sym24/round-30/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

