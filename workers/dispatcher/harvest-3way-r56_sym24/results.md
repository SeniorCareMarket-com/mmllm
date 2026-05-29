# harvest-3way-r56 — sparse-delta merge of 3 birds

## Worker endpoints

| handle | branch | R56 ctrl_bpc |
|--------|--------|--------------:|
| oQhDb | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-a352cb98-oQhDb | 3.3721 |
| UFitV | origin/claude/train-sym24-d137ea08-UFitV | 3.3770 |
| WwK9L | fork-joly-os-mmllm-claude-train-sym24-46bdd37b-WwK9L | 3.4451 |
| **mean** | | **3.3981** |
| **best** | | **3.3721** |

## Chain progression R54 → R56

Previous harvest: `workers/dispatcher/harvest-5way-r54_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 3.6088         | 3.3981         | -0.2107 |
| ctrl_bpc best  | 3.5621         | 3.3721         | -0.1900 |

## Per-round trajectory (best bird: oQhDb)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 55 | 1228 | 3.4854 | +0.0052 |
| 56 | 1344 | 3.3721 | +0.0249 |

## Cumulative training contribution

- This harvest: **60 steps** from 3 bird(s)
- Across full ancestry (deduped by bird_id): **200 steps** from 10 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-5way-r54_sym24`

## Output

`workers/dispatcher/harvest-3way-r56_sym24/round-56/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 3 workers)
- `dense.pt` (averaged across 3 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

