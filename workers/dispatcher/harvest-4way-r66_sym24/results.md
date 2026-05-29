# harvest-4way-r66 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R66 ctrl_bpc |
|--------|--------|--------------:|
| sLCGf | fork-slaa-us-mmllm-claude-train-sym24-1174bfb8-sLCGf | 3.2269 |
| GWC2l | origin/claude/train-sym24-ef29c173-GWC2l | 3.2353 |
| dbsOY | origin/claude/train-sym24-f81efb91-dbsOY | 3.2846 |
| zK1sj | fork-davidwuchn-mmllm-claude-train-sym24-bac47b66-zK1sj | 3.3656 |
| **mean** | | **3.2781** |
| **best** | | **3.2269** |

## Chain progression R64 → R66

Previous harvest: `workers/dispatcher/harvest-3way-r64_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4312         | 3.2781         | -0.1531 |
| ctrl_bpc best  | 3.3330         | 3.2269         | -0.1061 |

## Per-round trajectory (best bird: sLCGf)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 65 | 1145 | 3.3123 | +0.0212 |
| 66 | 1222 | 3.2269 | +0.0223 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r64_sym24`

## Output

`workers/dispatcher/harvest-4way-r66_sym24/round-66/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

