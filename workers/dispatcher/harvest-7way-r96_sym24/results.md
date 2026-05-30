# harvest-7way-r96 — sparse-delta merge of 7 birds

## Worker endpoints

| handle | branch | R96 ctrl_bpc |
|--------|--------|--------------:|
| rsopY | fork-slaa-us-mmllm-claude-train-sym24-1c9295a3-rsopY | 3.1074 |
| K3tsH | fork-joly-os-mmllm-claude-train-sym24-b41b16dc-K3tsH | 3.1934 |
| nVC8y | origin/claude/train-sym24-38248883-nVC8y | 3.2131 |
| YArpx | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-cc78becc-YArpx | 3.2406 |
| lKMf0 | fork-slaa-us-mmllm-claude-train-sym24-a66687cb-lKMf0 | 3.2591 |
| qfEBw | fork-davidwuchn-mmllm-claude-train-sym24-bf99659e-qfEBw | 3.2845 |
| vhvD4 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-a7223b05-vhvD4 | 3.4236 |
| **mean** | | **3.2460** |
| **best** | | **3.1074** |

## Per-round trajectory (best bird: rsopY)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 95 | 1266 | 3.0736 | +0.0560 |
| 96 | 1167 | 3.1074 | +0.0083 |

## Cumulative training contribution

- This harvest: **140 steps** from 7 bird(s)
- Across full ancestry (deduped by bird_id): **140 steps** from 7 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-6way-r94_sym24`

## Output

`workers/dispatcher/harvest-7way-r96_sym24/round-96/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 7 workers)
- `dense.pt` (averaged across 7 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

