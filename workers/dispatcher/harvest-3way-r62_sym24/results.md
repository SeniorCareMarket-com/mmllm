# harvest-3way-r62 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R62 ctrl_bpc |
|--------|--------|--------------:|
| D7fpt | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-bb020f70-D7fpt | 3.3646 |
| FlxQj | fork-joly-os-mmllm-claude-train-sym24-8a503f23-FlxQj | 3.3743 |
| xWAhb | origin/claude/train-sym24-17c08ebf-xWAhb | 3.5402 |
| **mean** | | **3.4264** |
| **best** | | **3.3646** |

## Chain progression R60 → R62

Previous harvest: `workers/dispatcher/harvest-4way-r60_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.4592         | 3.4264         | -0.0328 |
| ctrl_bpc best  | 3.3006         | 3.3646         | +0.0640 |

## Per-round trajectory (best bird: D7fpt)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 61 | 1264 | 3.3579 | +0.0220 |
| 62 | 1174 | 3.3646 | +0.0279 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **260 steps** from 13 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-4way-r60_sym24`

## Output

`workers/dispatcher/harvest-3way-r62_sym24/round-62/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

