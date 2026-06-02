# harvest-4way-r217 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R217 ctrl_bpc |
|--------|--------|--------------:|
| 86bHq | fork-davidwuchn-mmllm-claude-train-sym24-d3364937-86bHq | 2.4754 |
| elBfp | fork-joly-os-mmllm-claude-train-sym24-a773d562-elBfp | 2.5074 |
| H8Vx6 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-2138847f-H8Vx6 | 2.6405 |
| eobar | fork-slaa-us-mmllm-claude-train-sym24-e03763ab-eobar | 2.9731 |
| **mean** | | **2.6491** |
| **best** | | **2.4754** |

## Chain progression R140 → R217

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.6491         | +0.5981 |
| ctrl_bpc best  | 1.8188         | 2.4754         | +0.6566 |

## Per-round trajectory (best bird: 86bHq)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 217 | 5862 | 2.4754 | +0.0109 |

## Cumulative training contribution

- This harvest: **200 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r216_sym24`

## Output

`workers/dispatcher/harvest-4way-r217_sym24/round-217/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

