# harvest-4way-r32 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R32 ctrl_bpc |
|--------|--------|--------------:|
| FpHcw | fork-joly-os-mmllm-claude-train-sym24-1d3d66e9-FpHcw | 3.5631 |
| LU7iQ | origin/claude/train-sym24-3ac90098-LU7iQ | 3.6731 |
| 4UrDS | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-a178b946-4UrDS | 3.7209 |
| vaWfb | fork-slaa-us-mmllm-claude-train-sym24-fab8ef34-vaWfb | 3.9067 |
| **mean** | | **3.7159** |
| **best** | | **3.5631** |

## Chain progression R30 → R32

Previous harvest: `workers/dispatcher/harvest-2way-r30_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.7177         | 3.7159         | -0.0017 |
| ctrl_bpc best  | 3.6637         | 3.5631         | -0.1006 |

## Per-round trajectory (best bird: FpHcw)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 31 | 1238 | 3.5368 | +0.0202 |
| 32 | 1223 | 3.5631 | +0.0249 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r30_sym24`

## Output

`workers/dispatcher/harvest-4way-r32_sym24/round-32/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

