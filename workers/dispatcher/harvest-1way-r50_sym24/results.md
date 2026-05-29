# harvest-1way-r50 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R50 ctrl_bpc |
|--------|--------|--------------:|
| bczMv | fork-slaa-us-mmllm-claude-train-sym24-93fba130-bczMv | 3.5756 |
| **mean** | | **3.5756** |
| **best** | | **3.5756** |

## Chain progression R48 → R50

Previous harvest: `workers/dispatcher/harvest-1way-r48_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.5859         | 3.5756         | -0.0103 |
| ctrl_bpc best  | 3.5859         | 3.5756         | -0.0103 |

## Per-round trajectory (best bird: bczMv)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 49 | 1174 | 3.5477 | +0.0254 |
| 50 | 1204 | 3.5756 | +0.0211 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **120 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r48_sym24`

## Output

`workers/dispatcher/harvest-1way-r50_sym24/round-50/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

