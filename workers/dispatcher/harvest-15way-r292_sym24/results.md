# harvest-15way-r292 — sparse-delta merge of 15 birds

## Worker endpoints

| handle | branch | R292 ctrl_bpc |
|--------|--------|--------------:|
| uvbDJ | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-940cef52-uvbDJ | 2.3132 |
| hrQ0s | fork-davidwuchn-mmllm-claude-train-sym24-e605029c-hrQ0s | 2.3155 |
| qU6Rf | fork-joly-os-mmllm-claude-train-sym24-83e19120-qU6Rf | 2.3161 |
| 3LVsN | fork-slaa-us-mmllm-claude-train-sym24-84efa454-3LVsN | 2.3221 |
| 5BpUy | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-a17f18d0-5BpUy | 2.3247 |
| b7Spk | fork-davidwuchn-mmllm-claude-train-sym24-6a044a9f-b7Spk | 2.3280 |
| uRh2H | fork-davidwuchn-mmllm-claude-train-sym24-ef30a1e9-uRh2H | 2.3305 |
| AtPqb | fork-joly-os-mmllm-claude-train-sym24-c4518dbc-AtPqb | 2.4825 |
| VIMKh | fork-SeniorCareMarket-mmllm-claude-train-sym24-15dec62d-VIMKh | 2.4832 |
| C1vs7 | fork-joly-os-mmllm-claude-train-sym24-b771d90d-C1vs7 | 2.7510 |
| z6yeU | fork-SeniorCareMarket-com-mmllm-claude-train-sym24-462e873b-z6yeU | 2.7514 |
| G6RW2 | fork-slaa-us-mmllm-claude-train-sym24-0b84adea-G6RW2 | 2.7533 |
| a1NVF | fork-SeniorCareMarket-mmllm-claude-train-sym24-9f204f5b-a1NVF | 2.7545 |
| V7nbK | fork-slaa-us-mmllm-claude-train-sym24-79177757-V7nbK | 2.7555 |
| wisa0 | fork-slaa-us-mmllm-claude-train-sym24-42ded9e5-wisa0 | 2.7557 |
| **mean** | | **2.5158** |
| **best** | | **2.3132** |

## Chain progression R140 → R292

Previous harvest: `workers/dispatcher/harvest-2way-merge-r140_sym24`

| metric         | prior          | this           | Δ        |
|----------------|---------------:|---------------:|---------:|
| ctrl_bpc mean  | 2.0510         | 2.5158         | +0.4649 |
| ctrl_bpc best  | 1.8188         | 2.3132         | +0.4944 |

## Per-round trajectory (best bird: uvbDJ)

| round | wall_s | ctrl_bpc | Δ_net   |
|-------|-------:|---------:|--------:|
| 292 | 5303 | 2.3132 | +0.0103 |

## Cumulative training contribution

- This harvest: **750 steps** from 15 bird(s)
- Across full ancestry (deduped by bird_id): **750 steps** from 15 unique bird(s)
- Ancestor harvest(s):
  - `workers/dispatcher/harvest-2way-r291_sym24`

## Output

`workers/dispatcher/harvest-15way-r292_sym24/round-292/`:
- `delta-sparse-net.{0..31}.pt` (row-aware FedAvg merge of 15 workers)
- `dense.pt` (averaged across 15 birds)
- Reference for delta encoding: `workers/dispatcher/harvest-0way-r0_sym24/round-0`

