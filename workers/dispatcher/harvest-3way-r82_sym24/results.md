# harvest-3way-r82 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R82 ctrl_bpc |
|--------|--------|--------------:|
| oX6Fq | fork-joly-os-mmllm-claude-train-sym24-f9e6c2fd-oX6Fq | 3.2458 |
| EhCe5 | fork-davidwuchn-mmllm-claude-train-sym24-3172bb98-EhCe5 | 3.3761 |
| fAl42 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-ada4d153-fAl42 | 3.4402 |
| **mean** | | **3.3540** |
| **best** | | **3.2458** |

## Per-round trajectory (best bird: oX6Fq)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 81 | 1274 | 3.1705 | +0.0364 |
| 82 | 1304 | 3.2458 | +0.0147 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **60 steps** from 3 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r80_sym24`

## Output

`workers/dispatcher/harvest-3way-r82_sym24/round-82/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

