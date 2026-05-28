# harvest-2way-r46 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R46 ctrl_bpc |
|--------|--------|--------------:|
| d8ol8 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-d7b03034-d8ol8 | 3.3206 |
| 7ynVh | origin/claude/train-sym24-871e01a7-7ynVh | 3.5440 |
| **mean** | | **3.4323** |
| **best** | | **3.3206** |

## Chain progression R44 → R46

Previous harvest: `workers/dispatcher/harvest-2way-r44_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4987         | 3.4323         | -0.0664 |
| ctrl_bpc best  | 3.4112         | 3.3206         | -0.0906 |

## Per-round trajectory (best bird: d8ol8)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 45 | 1223 | 3.4637 | +0.0267 |
| 46 | 1235 | 3.3206 | +0.0200 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **120 steps** from 6 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r44_sym24`

## Output

`workers/dispatcher/harvest-2way-r46_sym24/round-46/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

