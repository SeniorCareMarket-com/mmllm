# harvest-5way-r104 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R104 ctrl_bpc |
|--------|--------|--------------:|
| OvbA1 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-c70e1c5e-OvbA1 | 3.1746 |
| v8tQk | fork-davidwuchn-mmllm-claude-train-sym24-f6d7d89d-v8tQk | 3.2440 |
| LfrwO | fork-slaa-us-mmllm-claude-train-sym24-7e4f877e-LfrwO | 3.2441 |
| LG5EX | fork-joly-os-mmllm-claude-train-sym24-892fd239-LG5EX | 3.2532 |
| PRTfx | origin/claude/train-sym24-e0bee1c7-PRTfx | 3.3034 |
| **mean** | | **3.2439** |
| **best** | | **3.1746** |

## Chain progression R102 → R104

Previous harvest: `workers/dispatcher/harvest-4way-r102_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2496         | 3.2439         | -0.0057 |
| ctrl_bpc best  | 3.1874         | 3.1746         | -0.0128 |

## Per-round trajectory (best bird: OvbA1)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 103 | 1246 | 3.3936 | +0.0197 |
| 104 | 1278 | 3.1746 | +0.0258 |

## Cumulative training contribution

- This harvest: **100 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **240 steps** from 12 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r102_sym24`

## Output

`workers/dispatcher/harvest-5way-r104_sym24/round-104/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

