# harvest-3way-r38 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R38 ctrl_bpc |
|--------|--------|--------------:|
| MHVCZ | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-0ff14c6d-MHVCZ | 3.4963 |
| tPWw5 | origin/claude/train-sym24-3f1b4237-tPWw5 | 3.6430 |
| BSUYI | fork-slaa-us-mmllm-claude-train-sym24-0b33660a-BSUYI | 3.6807 |
| **mean** | | **3.6067** |
| **best** | | **3.4963** |

## Chain progression R36 → R38

Previous harvest: `workers/dispatcher/harvest-4way-r36_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.6575         | 3.6067         | -0.0508 |
| ctrl_bpc best  | 3.5657         | 3.4963         | -0.0694 |

## Per-round trajectory (best bird: MHVCZ)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 37 | 1220 | 3.5313 | +0.0117 |
| 38 | 1244 | 3.4963 | +0.0187 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **300 steps** from 15 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r36_sym24`

## Output

`workers/dispatcher/harvest-3way-r38_sym24/round-38/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

