# harvest-2way-r179 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R179 ctrl_bpc |
|--------|--------|--------------:|
| vJbrU | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-f4b42070-vJbrU | 2.7776 |
| lJvAN | fork-davidwuchn-mmllm-claude-train-sym24-8321d52a-lJvAN | 3.2382 |
| **mean** | | **3.0079** |
| **best** | | **2.7776** |

## Chain progression R140 → R179

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 3.0079         | +0.9569 |
| ctrl_bpc best  | 1.8188         | 2.7776         | +0.9588 |

## Per-round trajectory (best bird: vJbrU)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 179 | 5309 | 2.7776 | +0.0195 |

## Cumulative training contribution

- This harvest: **100 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **100 steps** from 2 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r178_sym24`

## Output

`workers/dispatcher/harvest-2way-r179_sym24/round-179/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

