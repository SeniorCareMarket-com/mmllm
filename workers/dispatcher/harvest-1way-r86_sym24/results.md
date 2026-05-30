# harvest-1way-r86 — sparse-delta merge of 1 birds

## Worker endpoints

| handle | branch | R86 ctrl_bpc |
|--------|--------|--------------:|
| n116z | fork-joly-os-mmllm-claude-train-sym24-434624fa-n116z | 3.3589 |
| **mean** | | **3.3589** |
| **best** | | **3.3589** |

## Chain progression R84 → R86

Previous harvest: `workers/dispatcher/harvest-5way-r84_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.3954         | 3.3589         | -0.0365 |
| ctrl_bpc best  | 3.3186         | 3.3589         | +0.0403 |

## Per-round trajectory (best bird: n116z)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 85 | 1240 | 3.3633 | +0.0030 |
| 86 | 1237 | 3.3589 | +0.0138 |

## Cumulative training contribution

- This harvest: **20 steps** from 1 bird(s)
- Across full ancestry (deduped by bird_id): **180 steps** from 9 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r84_sym24`

## Output

`workers/dispatcher/harvest-1way-r86_sym24/round-86/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 1 workers)
- `dense.pt` (averaged across 1 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

