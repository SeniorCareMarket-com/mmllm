# harvest-4way-r34 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R34 ctrl_bpc |
|--------|--------|--------------:|
| Jr3bc | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-6e64804c-Jr3bc | 3.6673 |
| 2KEfS | origin/claude/train-sym24-40bd226e-2KEfS | 3.7104 |
| WbL9R | fork-joly-os-mmllm-claude-train-sym24-4363d55d-WbL9R | 3.7314 |
| prhwr | fork-slaa-us-mmllm-claude-train-sym24-47e552cb-prhwr | 3.7473 |
| **mean** | | **3.7141** |
| **best** | | **3.6673** |

## Chain progression R32 → R34

Previous harvest: `workers/dispatcher/harvest-4way-r32_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.7159         | 3.7141         | -0.0018 |
| ctrl_bpc best  | 3.5631         | 3.6673         | +0.1042 |

## Per-round trajectory (best bird: Jr3bc)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 33 | 1245 | 3.5669 | +0.0178 |
| 34 | 1329 | 3.6673 | +0.0177 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r32_sym24`

## Output

`workers/dispatcher/harvest-4way-r34_sym24/round-34/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

