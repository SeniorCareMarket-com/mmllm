# harvest-5way-r122 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R122 ctrl_bpc |
|--------|--------|--------------:|
| h91wU | origin/claude/train-sym24-0b9e8505-h91wU | 2.7829 |
| onqvi | fork-slaa-us-mmllm-claude-train-sym24-f621142a-onqvi | 2.8132 |
| Nu6A4 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-a76e7649-Nu6A4 | 2.8253 |
| OWQWE | fork-joly-os-mmllm-claude-train-sym24-d4d26f22-OWQWE | 2.8284 |
| LEANV | origin/claude/train-sym24-0030d9d6-LEANV | 2.9900 |
| **mean** | | **2.8480** |
| **best** | | **2.7829** |

## Chain progression R121 → R122

Previous harvest: `workers/dispatcher/harvest-1way-r121_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.9078         | 2.8480         | -0.0598 |
| ctrl_bpc best  | 2.9078         | 2.7829         | -0.1249 |

## Per-round trajectory (best bird: h91wU)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 122 | 5777 | 2.7829 | +0.1665 |

## Cumulative training contribution

- This harvest: **250 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **400 steps** from 8 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r121_sym24`

## Output

`workers/dispatcher/harvest-5way-r122_sym24/round-122/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

