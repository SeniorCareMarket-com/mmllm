# harvest-3way-r126 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R126 ctrl_bpc |
|--------|--------|--------------:|
| i74sR | fork-slaa-us-mmllm-claude-train-sym24-be539a09-i74sR | 2.5824 |
| qkAmK | fork-davidwuchn-mmllm-claude-train-sym24-75594ec2-qkAmK | 2.6279 |
| xixMg | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-d00f483f-xixMg | 2.6400 |
| **mean** | | **2.6168** |
| **best** | | **2.5824** |

## Chain progression R125 → R126

Previous harvest: `workers/dispatcher/harvest-3way-r125_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.5989         | 2.6168         | +0.0179 |
| ctrl_bpc best  | 2.4289         | 2.5824         | +0.1535 |

## Per-round trajectory (best bird: i74sR)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 126 | 4754 | 2.5824 | +0.2378 |

## Cumulative training contribution

- This harvest: **150 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **600 steps** from 12 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r125_sym24`

## Output

`workers/dispatcher/harvest-3way-r126_sym24/round-126/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

