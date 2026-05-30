# harvest-3way-r88 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R88 ctrl_bpc |
|--------|--------|--------------:|
| wvkqe | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-95156778-wvkqe | 3.3167 |
| L3Ojw | fork-slaa-us-mmllm-claude-train-sym24-5ccafb92-L3Ojw | 3.4173 |
| 7ffM0 | fork-davidwuchn-mmllm-claude-train-sym24-13d54e77-7ffM0 | 3.4204 |
| **mean** | | **3.3848** |
| **best** | | **3.3167** |

## Chain progression R86 → R88

Previous harvest: `workers/dispatcher/harvest-1way-r86_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3589         | 3.3848         | +0.0259 |
| ctrl_bpc best  | 3.3589         | 3.3167         | -0.0422 |

## Per-round trajectory (best bird: wvkqe)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 87 | 1254 | 3.3750 | +0.0025 |
| 88 | 1219 | 3.3167 | -0.0002 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 10 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r86_sym24`

## Output

`workers/dispatcher/harvest-3way-r88_sym24/round-88/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

