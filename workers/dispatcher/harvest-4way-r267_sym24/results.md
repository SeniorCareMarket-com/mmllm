# harvest-4way-r267 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R267 ctrl_bpc |
|--------|--------|--------------:|
| 4oDyk | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-55bfaf75-4oDyk | 2.3379 |
| blTar | fork-joly-os-mmllm-claude-train-sym24-60d7230f-blTar | 2.3411 |
| hxhbG | fork-slaa-us-mmllm-claude-train-sym24-e8e77b33-hxhbG | 2.3430 |
| fXvEJ | fork-davidwuchn-mmllm-claude-train-sym24-a0dcefd5-fXvEJ | 2.7768 |
| **mean** | | **2.4497** |
| **best** | | **2.3379** |

## Chain progression R140 → R267

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.4497         | +0.3987 |
| ctrl_bpc best  | 1.8188         | 2.3379         | +0.5191 |

## Per-round trajectory (best bird: 4oDyk)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 267 | 5176 | 2.3379 | +0.0083 |

## Cumulative training contribution

- This harvest: **200 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r266_sym24`

## Output

`workers/dispatcher/harvest-4way-r267_sym24/round-267/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

