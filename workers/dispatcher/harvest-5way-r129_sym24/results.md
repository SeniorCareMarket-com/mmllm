# harvest-5way-r129 — sparse-delta merge of 5 birds

## Worker endpoints

| handle | branch | R129 ctrl_bpc |
|--------|--------|--------------:|
| jVbLT | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-31d75d60-jVbLT | 2.3107 |
| oJqob | fork-davidwuchn-mmllm-claude-train-sym24-e0db1a41-oJqob | 2.6198 |
| CISM3 | origin/claude/train-sym24-450e7497-CISM3 | 2.6666 |
| 4db5R | origin/claude/train-sym24-0e0ef762-4db5R | 2.6857 |
| CISM2 | origin/claude/train-sym24-81487642-CISM2 | — |
| **mean** | | **2.5707** |
| **best** | | **2.3107** |

## Chain progression R128 → R129

Previous harvest: `workers/dispatcher/harvest-1way-r128_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.6767         | 2.5707         | -0.1060 |
| ctrl_bpc best  | 2.6767         | 2.3107         | -0.3660 |

## Per-round trajectory (best bird: jVbLT)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 129 | 5529 | 2.3107 | +0.2954 |

## Cumulative training contribution

- This harvest: **170 steps** from 5 bird(s)
- Across full ancestry (deduped by bird_id): **470 steps** from 11 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-1way-r128_sym24`

## Output

`workers/dispatcher/harvest-5way-r129_sym24/round-129/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 5 workers)
- `dense.pt` (averaged across 5 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

