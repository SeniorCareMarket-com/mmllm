# harvest-4way-r102 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R102 ctrl_bpc |
|--------|--------|--------------:|
| v2J2f | fork-joly-os-mmllm-claude-train-sym24-6c43687b-v2J2f | 3.1874 |
| R9Bc1 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-5ade15e5-R9Bc1 | 3.2183 |
| thmAO | fork-davidwuchn-mmllm-claude-train-sym24-310575f4-thmAO | 3.2201 |
| 5ogy6 | fork-slaa-us-mmllm-claude-train-sym24-19ac8cc9-5ogy6 | 3.3724 |
| **mean** | | **3.2496** |
| **best** | | **3.1874** |

## Chain progression R100 → R102

Previous harvest: `workers/dispatcher/harvest-2way-r100_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2610         | 3.2496         | -0.0114 |
| ctrl_bpc best  | 3.2024         | 3.1874         | -0.0150 |

## Per-round trajectory (best bird: v2J2f)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 101 | 1309 | 3.2455 | +0.0461 |
| 102 | 1175 | 3.1874 | +0.0266 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 10 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r100_sym24`

## Output

`workers/dispatcher/harvest-4way-r102_sym24/round-102/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

