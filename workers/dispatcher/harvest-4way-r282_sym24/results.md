# harvest-4way-r282 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R282 ctrl_bpc |
|--------|--------|--------------:|
| fkGLv | fork-joly-os-mmllm-claude-train-sym24-89fbac4b-fkGLv | 2.4865 |
| ni7J3 | fork-slaa-us-mmllm-claude-train-sym24-7af21fff-ni7J3 | 2.4872 |
| DyBHG | fork-davidwuchn-mmllm-claude-train-sym24-21939c81-DyBHG | 2.7613 |
| dV7n4 | fork-SeniorCareMarket-mmllm-claude-train-sym24-b45b6680-dV7n4 | 2.7665 |
| **mean** | | **2.6254** |
| **best** | | **2.4865** |

## Chain progression R281 → R282

Previous harvest: `workers/dispatcher/harvest-2way-r281_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.4234         | 2.6254         | +0.2020 |
| ctrl_bpc best  | 2.3371         | 2.4865         | +0.1494 |

## Per-round trajectory (best bird: fkGLv)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 282 | 4542 | 2.4865 | +0.0093 |

## Cumulative training contribution

- This harvest: **200 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r281_sym24`

## Output

`workers/dispatcher/harvest-4way-r282_sym24/round-282/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

