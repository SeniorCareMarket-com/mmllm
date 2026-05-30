# harvest-3way-r96 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R96 ctrl_bpc |
|--------|--------|--------------:|
| nVC8y | origin/claude/train-sym24-38248883-nVC8y | 3.2131 |
| YArpx | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-cc78becc-YArpx | 3.2406 |
| lKMf0 | fork-slaa-us-mmllm-claude-train-sym24-a66687cb-lKMf0 | 3.2591 |
| **mean** | | **3.2376** |
| **best** | | **3.2131** |

## Chain progression R94 → R96

Previous harvest: `workers/dispatcher/harvest-6way-r94_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2242         | 3.2376         | +0.0134 |
| ctrl_bpc best  | 3.0797         | 3.2131         | +0.1334 |

## Per-round trajectory (best bird: nVC8y)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 95 | 1263 | 3.2008 | +0.0357 |
| 96 | 1195 | 3.2131 | -0.0242 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-6way-r94_sym24`

## Output

`workers/dispatcher/harvest-3way-r96_sym24/round-96/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

