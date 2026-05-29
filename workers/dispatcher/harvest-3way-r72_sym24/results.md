# harvest-3way-r72 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R72 ctrl_bpc |
|--------|--------|--------------:|
| RjS9F | fork-slaa-us-mmllm-claude-train-sym24-75c4be60-RjS9F | 3.3428 |
| P0jsf | fork-joly-os-mmllm-claude-train-sym24-098a99bb-P0jsf | 3.3879 |
| BWehr | fork-davidwuchn-mmllm-claude-train-sym24-2a885280-BWehr | 3.4872 |
| **mean** | | **3.4060** |
| **best** | | **3.3428** |

## Chain progression R70 → R72

Previous harvest: `workers/dispatcher/harvest-4way-r70_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3819         | 3.4060         | +0.0241 |
| ctrl_bpc best  | 3.3157         | 3.3428         | +0.0271 |

## Per-round trajectory (best bird: RjS9F)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 71 | 1354 | 3.3186 | +0.0106 |
| 72 | 1158 | 3.3428 | +0.0007 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **300 steps** from 15 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r70_sym24`

## Output

`workers/dispatcher/harvest-3way-r72_sym24/round-72/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

