# harvest-4way-r106 — sparse-delta merge of 4 birds

## Worker endpoints

| handle | branch | R106 ctrl_bpc |
|--------|--------|--------------:|
| 7yPDf | fork-joly-os-mmllm-claude-train-sym24-ff18f91c-7yPDf | 3.1643 |
| vM396 | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-d54e5c9f-vM396 | 3.1902 |
| E4yzo | fork-slaa-us-mmllm-claude-train-sym24-18b0324f-E4yzo | 3.2272 |
| Fl1cL | fork-davidwuchn-mmllm-claude-train-sym24-fbc75f07-Fl1cL | 3.2495 |
| **mean** | | **3.2078** |
| **best** | | **3.1643** |

## Chain progression R104 → R106

Previous harvest: `workers/dispatcher/harvest-5way-r104_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.2439         | 3.2078         | -0.0361 |
| ctrl_bpc best  | 3.1746         | 3.1643         | -0.0103 |

## Per-round trajectory (best bird: 7yPDf)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 105 | 1236 | 3.2831 | -0.0200 |
| 106 | 1222 | 3.1643 | +0.0142 |

## Cumulative training contribution

- This harvest: **80 steps** from 4 bird(s)
- Across full ancestry (deduped by bird_id): **300 steps** from 15 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r104_sym24`

## Output

`workers/dispatcher/harvest-4way-r106_sym24/round-106/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 4 workers)
- `dense.pt` (averaged across 4 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

