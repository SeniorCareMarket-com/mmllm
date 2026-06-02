# harvest-4way-r199 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R199 ctrl_bpc |
|--------|--------|--------------:|
| NhsdR | fork-joly-os-mmllm-claude-train-sym24-b3b7c9e5-NhsdR | 2.6142 |
| AfLEs | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-1d62e162-AfLEs | 2.6232 |
| S7J4g | fork-slaa-us-mmllm-claude-train-sym24-b326d668-S7J4g | 2.6535 |
| 29a4S | fork-davidwuchn-mmllm-claude-train-sym24-05505f82-29a4S | 3.0985 |
| **mean** | | **2.7473** |
| **best** | | **2.6142** |

## Chain progression R140 → R199

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.7473         | +0.6964 |
| ctrl_bpc best  | 1.8188         | 2.6142         | +0.7954 |

## Per-round trajectory (best bird: NhsdR)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 199 | 5686 | 2.6142 | +0.0081 |

## Cumulative training contribution

- This harvest: **200 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 4 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r198_sym24`

## Output

`workers/dispatcher/harvest-4way-r199_sym24/round-199/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

