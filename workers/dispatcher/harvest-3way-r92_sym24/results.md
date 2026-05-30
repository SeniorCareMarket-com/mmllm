# harvest-3way-r92 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R92 ctrl_bpc |
|--------|--------|--------------:|
| X7qlU | fork-davidwuchn-mmllm-claude-train-sym24-b1c55314-X7qlU | 3.2046 |
| BoVqL | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-55fc428f-BoVqL | 3.2371 |
| xJ2IJ | origin/claude/train-sym24-f3cbfbfa-xJ2IJ | 3.3205 |
| **mean** | | **3.2541** |
| **best** | | **3.2046** |

## Chain progression R90 → R92

Previous harvest: `workers/dispatcher/harvest-2way-r90_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2111         | 3.2541         | +0.0430 |
| ctrl_bpc best  | 3.1688         | 3.2046         | +0.0358 |

## Per-round trajectory (best bird: X7qlU)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 91 | 1245 | 3.2277 | +0.0110 |
| 92 | 1224 | 3.2046 | +0.0134 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **180 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r90_sym24`

## Output

`workers/dispatcher/harvest-3way-r92_sym24/round-92/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

