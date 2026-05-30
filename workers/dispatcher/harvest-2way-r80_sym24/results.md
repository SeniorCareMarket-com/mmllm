# harvest-2way-r80 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R80 ctrl_bpc |
|--------|--------|--------------:|
| L33xg | fork-slaa-us-mmllm-claude-train-sym24-fda1cad6-L33xg | 3.4086 |
| lV0lz | fork-davidwuchn-mmllm-claude-train-sym24-67dd7d2e-lV0lz | 3.5300 |
| **mean** | | **3.4693** |
| **best** | | **3.4086** |

## Chain progression R78 → R80

Previous harvest: `workers/dispatcher/harvest-2way-r78_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3682         | 3.4693         | +0.1011 |
| ctrl_bpc best  | 3.3395         | 3.4086         | +0.0691 |

## Per-round trajectory (best bird: L33xg)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 79 | 1272 | 3.4470 | +0.0172 |
| 80 | 1252 | 3.4086 | +0.0420 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **140 steps** from 7 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r78_sym24`

## Output

`workers/dispatcher/harvest-2way-r80_sym24/round-80/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

