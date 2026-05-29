# harvest-2way-r74 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R74 ctrl_bpc |
|--------|--------|--------------:|
| g8czP | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-a210d199-g8czP | 3.3058 |
| KSCj4 | origin/claude/train-sym24-c0c460a5-KSCj4 | 3.3590 |
| **mean** | | **3.3324** |
| **best** | | **3.3058** |

## Chain progression R72 → R74

Previous harvest: `workers/dispatcher/harvest-3way-r72_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4060         | 3.3324         | -0.0736 |
| ctrl_bpc best  | 3.3428         | 3.3058         | -0.0370 |

## Per-round trajectory (best bird: g8czP)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 73 | 1285 | 3.3066 | +0.0236 |
| 74 | 1221 | 3.3058 | -0.0125 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **260 steps** from 13 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r72_sym24`

## Output

`workers/dispatcher/harvest-2way-r74_sym24/round-74/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

