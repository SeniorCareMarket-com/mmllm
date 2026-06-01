# harvest-3way-r130 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R130 ctrl_bpc |
|--------|--------|--------------:|
| ow2WF | fork-joly-os-mmllm-claude-train-sym24-bd85a44a-ow2WF | 2.2831 |
| mpZLR | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-ee7b50fe-mpZLR | 2.4975 |
| zbEgG | fork-slaa-us-mmllm-claude-train-sym24-38a9bfc5-zbEgG | 2.6231 |
| **mean** | | **2.4679** |
| **best** | | **2.2831** |

## Chain progression R129 → R130

Previous harvest: `workers/dispatcher/harvest-5way-r129_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.5707         | 2.4679         | -0.1028 |
| ctrl_bpc best  | 2.3107         | 2.2831         | -0.0276 |

## Per-round trajectory (best bird: ow2WF)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 130 | 5747 | 2.2831 | +0.2979 |

## Cumulative training contribution

- This harvest: **150 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **370 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r129_sym24`

## Output

`workers/dispatcher/harvest-3way-r130_sym24/round-130/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

