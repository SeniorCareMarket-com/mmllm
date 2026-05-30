# harvest-2way-r90 — sparse-delta merge of 2 birds

## Worker endpoints

| handle | branch | R90 ctrl_bpc |
|--------|--------|--------------:|
| hha3U | fork-slaa-us-mmllm-claude-train-sym24-8df6a970-hha3U | 3.1688 |
| fSMNS | fork-joly-os-mmllm-claude-train-sym24-2f331541-fSMNS | 3.2535 |
| **mean** | | **3.2111** |
| **best** | | **3.1688** |

## Chain progression R88 → R90

Previous harvest: `workers/dispatcher/harvest-3way-r88_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3848         | 3.2111         | -0.1736 |
| ctrl_bpc best  | 3.3167         | 3.1688         | -0.1479 |

## Per-round trajectory (best bird: hha3U)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 89 | 1104 | 3.1730 | +0.0013 |
| 90 | 1194 | 3.1688 | +0.0423 |

## Cumulative training contribution

- This harvest: **40 steps** from 2 bird(s)
- Across full ancestry (deduped by bird_id): **220 steps** from 11 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r88_sym24`

## Output

`workers/dispatcher/harvest-2way-r90_sym24/round-90/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 2 workers)
- `dense.pt` (averaged across 2 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

