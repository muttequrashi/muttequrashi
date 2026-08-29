<div align="center">

# MUTTE UR REHMAN

### Independent AI Engineer · Paris, France

[![Available for work](https://img.shields.io/badge/AVAILABLE_FOR-SELECTED_PROJECTS-00d084?style=flat-square)](mailto:mutte.rehman@vnexia.com)
[![Built different](https://img.shields.io/badge/BUILT_DIFFERENT-BY_DEFAULT-111111?style=flat-square)](#)
[![YOLO](https://img.shields.io/badge/YOLO-BADGE_LIFESTYLE-f2c94c?style=flat-square)](#)

<br />

> I build the seam between intelligent software and physical systems.

<br />

</div>

---

## The short version

I work across the layers most teams keep separate:

| `01` | LLM systems |
| --- | --- |
|  | Agents, evaluation, MCP, orchestration, APIs |

| `02` | Edge vision |
| --- | --- |
|  | Real-time cameras, Jetson pipelines, TensorRT, computer vision |

| `03` | Firmware + hardware |
| --- | --- |
|  | ESP32, STM32, LoRaWAN, BLE, PCBs, field deployments |

The interesting work happens where these layers meet.

That is where latency becomes a product decision.  
Where a model needs to survive bad connectivity.  
Where a prototype has to keep working at 2am on a Sunday.

---

## What runs where

```console
$ docker ps

CONTAINER      IMAGE                        UPTIME        PORT
tuple-tech     studio/end-to-end            2 months      :shipping
consulting     eu/industrial                7 years       :sprints
h2-drone       confidential/vtol            3 years       :computer-vision
this-profile   me/independent               24/7          :hire-me
```

---

## How I decide what to build

```python
from mutte import ship

@ship.to_production
def solve(problem):
    if problem.needs("real-time cameras"):
        return jetson_pipeline(
            quantize="int8",
            latency_ms=30,
        )

    if problem.has("llm") and problem.hates("hallucination"):
        return agent(
            evals=True,
            cost_ceiling="$0.02/query",
        )

    if problem.involves("hardware"):
        return firmware(
            survives="2am on a Sunday",
        )

    if problem.smells_like("3 vendors passing files"):
        return "let me be one of them instead"

    return coffee_and_a_scope()
```

---

## Field report

*Anonymized because clients still pay their invoices.*

| Project | What shipped | Scale | Status |
| --- | --- | --- | --- |
| **Industrial safety** | Multi-camera computer vision | 4+ streams · 30 FPS · edge | `ongoing` |
| **H2 VTOL drone** | On-device computer vision | Confidential | `2022 →` |
| **LoRaWAN fleet** | ESP32 · PCB · cloud | Field deployment · EU | `2025` |
| **Floor visualizer** | SAM 2 · homography · web | MVP | `2026` |
| **This README** | ASCII art · opinions | 1 profile · 0 regrets | `today` |

<details>
<summary><strong>What I actually care about</strong></summary>

<br />

- Making intelligent systems dependable outside the demo.
- Reducing the distance between prototype and production.
- Choosing on-device inference when latency, cost, or bandwidth demands it.
- Removing unnecessary handoffs between software, hardware, and operations.
- Building systems that are understandable enough to maintain.

</details>

---

## The manifesto

```text
01  The model is 20% of the work.
02  The seam is the other 80%.
03  On-device wins when latency, cost, or bandwidth says so.
04  Three vendors is two too many.
05  Don't be a hero. Be on call.
```

---

## Stack, quickly

<table>
<tr>
<td valign="top" width="25%">

### Agents

- LangGraph
- Google ADK
- MCP
- A2A
- FastAPI
- Postgres

</td>
<td valign="top" width="25%">

### Vision

- PyTorch
- TensorRT
- DeepStream
- SAM 2
- Jetson
- Coral

</td>
<td valign="top" width="25%">

### Firmware

- ESP32
- STM32
- Zephyr
- LoRaWAN
- BLE
- KiCad

</td>
<td valign="top" width="25%">

### Glue

- Python
- C++17
- CUDA
- Docker
- AWS
- GCP

</td>
</tr>
</table>

---

## Currently open for

`2–3 day sprints` · `MVPs in 4–8 weeks` · `discovery calls` · `second opinions`

## Currently not open for

`staff augmentation` · `tickets in a queue` · `unpaid trials` · `crypto`

---

## Reach me

<div align="center">

### Have a difficult seam?

[**muttequrashi.github.io**](https://muttequrashi.github.io)  
[**linkedin.com/in/mutte-ur-rahman**](https://linkedin.com/in/mutte-ur-rahman)  
**mutte.rehman [at] vnexia [dot] com**

<br />

<sub>YOLO badge above this README is a lifestyle, not a bug.</sub>

</div>
