# harvest-4way-r287 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R287 ctrl_bpc |
|--------|--------|--------------:|
| zsycz | fork-joly-os-mmllm-claude-train-sym24-34585ed1-zsycz | 2.3184 |
| dI2JK | fork-slaa-us-mmllm-claude-train-sym24-2f3360ca-dI2JK | 2.3214 |
| 3yii7 | fork-davidwuchn-mmllm-claude-train-sym24-0487175b-3yii7 | 2.3297 |
| Kt92w | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-4ffadc93-Kt92w | 2.4823 |
| **mean** | | **2.3629** |
| **best** | | **2.3184** |

## Chain progression R286 → R287

Previous harvest: `workers/dispatcher/harvest-2way-r286_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.5563         | 2.3629         | -0.1934 |
| ctrl_bpc best  | 2.3361         | 2.3184         | -0.0177 |

## Per-round trajectory (best bird: zsycz)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 287 | 5430 | 2.3184 | +0.0078 |

## Cumulative training contribution

- This harvest: **200 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r286_sym24`

## Output

`workers/dispatcher/harvest-4way-r287_sym24/round-287/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

