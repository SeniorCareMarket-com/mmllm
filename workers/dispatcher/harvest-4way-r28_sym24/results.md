# harvest-4way-r28 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R28 ctrl_bpc |
|--------|--------|--------------:|
| nic3l | fork-joly-os-mmllm-claude-train-sym24-2f0fd744-nic3l | 3.7014 |
| QAyEK | origin/claude/train-sym24-27734132-QAyEK | 3.7161 |
| 1J5AO | fork-slaa-us-mmllm-claude-train-sym24-e0114ddd-1J5AO | 3.7909 |
| w9Ulm | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-1c427ece-w9Ulm | 3.8081 |
| **mean** | | **3.7541** |
| **best** | | **3.7014** |

## Chain progression R26 → R28

Previous harvest: `workers/dispatcher/harvest-4way-r26_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.7086         | 3.7541         | +0.0455 |
| ctrl_bpc best  | 3.5302         | 3.7014         | +0.1712 |

## Per-round trajectory (best bird: nic3l)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 27 | 1090 | 3.7378 | +0.0132 |
| 28 | 1086 | 3.7014 | +0.0089 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **320 steps** from 16 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r26_sym24`

## Output

`workers/dispatcher/harvest-4way-r28_sym24/round-28/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

