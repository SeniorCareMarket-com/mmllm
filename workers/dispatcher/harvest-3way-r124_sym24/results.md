# harvest-3way-r124 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R124 ctrl_bpc |
|--------|--------|--------------:|
| JoUM7 | fork-slaa-us-mmllm-claude-train-sym24-73b8974a-JoUM7 | 2.5291 |
| LFPVs | origin/claude/train-sym24-c3fa37bb-LFPVs | 2.7352 |
| OaZYJ | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-69df63c2-OaZYJ | 2.7574 |
| **mean** | | **2.6739** |
| **best** | | **2.5291** |

## Chain progression R123 → R124

Previous harvest: `workers/dispatcher/harvest-3way-r123_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.9264         | 2.6739         | -0.2525 |
| ctrl_bpc best  | 2.8195         | 2.5291         | -0.2904 |

## Per-round trajectory (best bird: JoUM7)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 124 | 6740 | 2.5291 | +0.1828 |

## Cumulative training contribution

- This harvest: **150 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **600 steps** from 12 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-3way-r123_sym24`

## Output

`workers/dispatcher/harvest-3way-r124_sym24/round-124/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

