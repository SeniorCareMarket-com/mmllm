# harvest-3way-r58 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R58 ctrl_bpc |
|--------|--------|--------------:|
| OVHoT | origin/claude/train-sym24-66baeacb-OVHoT | 3.4454 |
| Wloya | fork-slaa-us-mmllm-claude-train-sym24-9fa3bc9c-Wloya | 3.4550 |
| xoayO | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-e930f305-xoayO | 3.5033 |
| **mean** | | **3.4679** |
| **best** | | **3.4454** |

## Chain progression R56 → R58

Previous harvest: `workers/dispatcher/harvest-3way-r56_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3981         | 3.4679         | +0.0698 |
| ctrl_bpc best  | 3.3721         | 3.4454         | +0.0733 |

## Per-round trajectory (best bird: OVHoT)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 57 | 1270 | 3.4797 | +0.0119 |
| 58 | 1254 | 3.4454 | +0.0142 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **240 steps** from 12 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r56_sym24`

## Output

`workers/dispatcher/harvest-3way-r58_sym24/round-58/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

