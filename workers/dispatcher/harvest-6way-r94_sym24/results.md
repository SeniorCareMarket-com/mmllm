# harvest-6way-r94 — sparse-delta merge of 6 birds

## Worker endpoints

| handle | branch | R94 ctrl_bpc |
|--------|--------|--------------:|
| IvcC2 | fork-joly-os-mmllm-claude-train-sym24-bea27b17-IvcC2 | 3.0797 |
| KgNh3 | fork-SeniorCareMarket-mmllm-claude-train-sym24-ddaf01c1-KgNh3 | 3.2081 |
| wqptE | fork-slaa-us-mmllm-claude-train-sym24-89172b81-wqptE | 3.2198 |
| nPXm5 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-06b7f71c-nPXm5 | 3.2418 |
| Q8Ca2 | origin/claude/train-sym24-1e0ac351-Q8Ca2 | 3.2735 |
| Z3dtw | fork-davidwuchn-mmllm-claude-train-sym24-346a3907-Z3dtw | 3.3224 |
| **mean** | | **3.2242** |
| **best** | | **3.0797** |

## Chain progression R92 → R94

Previous harvest: `workers/dispatcher/harvest-3way-r92_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2541         | 3.2242         | -0.0299 |
| ctrl_bpc best  | 3.2046         | 3.0797         | -0.1249 |

## Per-round trajectory (best bird: IvcC2)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 93 | 1088 | 3.0596 | +0.0489 |
| 94 | 1063 | 3.0797 | +0.0353 |

## Cumulative training contribution

- This harvest: **120 steps** from 6 bird(s)
- Across full ancestry (deduped by bird_id): **280 steps** from 14 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r92_sym24`

## Output

`workers/dispatcher/harvest-6way-r94_sym24/round-94/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 6 workers)
- `dense.pt` (averaged across 6 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

