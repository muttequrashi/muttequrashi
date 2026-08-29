<div align="center">

# MUTTE UR REHMAN

### Independent AI Engineer · Paris, France

[![Available for work](https://img.shields.io/badge/AVAILABLE_FOR-SELECTED_PROJECTS-00d084?style=flat-square)](mailto:mutte.rehman@vnexia.com)
[![Built different](https://img.shields.io/badge/BUILT_DIFFERENT-BY_DEFAULT-111111?style=flat-square)](#)
[![YOLO](https://img.shields.io/badge/YOLO-BADGE_LIFESTYLE-f2c94c?style=flat-square)](#)

<br />

> I turn AI ideas into reliable products — from model to machine.

<br />

</div>

---

## What I do

<table>
<tr>
<td valign="top" width="33%">

### AI systems

LLM agents, evaluation, orchestration, MCP, APIs, and production backends.

</td>
<td valign="top" width="33%">

### Edge vision

Real-time camera pipelines, on-device inference, TensorRT, DeepStream, and Jetson.

</td>
<td valign="top" width="33%">

### Embedded systems

Firmware, sensors, PCBs, ESP32, STM32, LoRaWAN, BLE, and field deployments.

</td>
</tr>
</table>

I connect software, models, and hardware into systems that work outside the demo:
fast enough, cheap enough, and reliable enough to ship.

---

## Working style

```console
$ systemctl status mutte

SERVICE        STATUS       MODE
consulting     active       focused sprints
computer-vision active      real-time · edge-first
embedded       active       hardware that ships
this-profile   always-on    open to the right problem
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
