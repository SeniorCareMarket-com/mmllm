# harvest-4way-r597 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R597 ctrl_bpc |
|--------|--------|--------------:|
| UYiP5 | fork-slaa-us-mmllm-claude-train-sym24-be5776b2-UYiP5 | 2.1408 |
| ALcd3 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-e3c55078-ALcd3 | 2.3540 |
| XwaHA | fork-davidwuchn-mmllm-claude-train-sym24-00349372-XwaHA | 2.3548 |
| AR9m8 | fork-joly-os-mmllm-claude-train-sym24-25657f9b-AR9m8 | 2.3572 |
| **mean** | | **2.3017** |
| **best** | | **2.1408** |

## Chain progression R596 → R597

Previous harvest: `workers/dispatcher/harvest-2way-r596_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.1913         | 2.3017         | +0.1104 |
| ctrl_bpc best  | 2.1796         | 2.1408         | -0.0388 |

## Per-round trajectory (best bird: UYiP5)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 597 | 5609 | 2.1408 | +0.0174 |

## Cumulative training contribution

- This harvest: **200 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r596_sym24`

## Output

`workers/dispatcher/harvest-4way-r597_sym24/round-597/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

