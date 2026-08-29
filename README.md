```
                    ╔══════════════════════════════════════════╗
                    ║           MUTTE UR REHMAN                ║
                    ║  independent ai engineer  ·  paris, fr   ║
                    ╚══════════════════════════════════════════╝
                                    │
                    ┌───────────────┼───────────────┐
                    ▼               ▼               ▼
              ┌──────────┐    ┌──────────┐    ┌──────────┐
              │   llm    │    │   edge   │    │ firmware │
              │  agents  │    │  vision  │    │   & pcb  │
              └────┬─────┘    └────┬─────┘    └────┬─────┘
                   └──────────────┬┴───────────────┘
                                  ▼
                       ╔══════════════════════╗
                       ║      the seam        ║
                       ║  where most projects ║
                       ║       break          ║
                       ╚══════════════════════╝
                                  │
                                  ▼
                            i live here.
```

## what runs where

```console
$ docker ps
CONTAINER      IMAGE                        UPTIME        PORT
tuple-tech     studio/end-to-end            2 months      :shipping
consulting     eu/industrial                7 years       :sprints
h2-drone       confidential/vtol            3 years       :computer-vision
this-profile   me/independent               24/7          :hire-me
```

## how I decide what to build

```python
from mutte import ship

@ship.to_production
def solve(problem):
    if problem.needs("real-time cameras"):
        return jetson_pipeline(quantize="int8", latency_ms=30)

    if problem.has("llm") and problem.hates("hallucination"):
        return agent(evals=True, cost_ceiling="$0.02/query")

    if problem.involves("hardware"):
        return firmware(survives="2am on a sunday")

    if problem.smells_like("3 vendors passing files"):
        return "let me be one of them instead"

    return coffee_and_a_scope()
```

## field report

Anonymized because clients still pay their invoices.

| project           | what           | scale                       | year    |
|-------------------|----------------|-----------------------------|---------|
| industrial safety | multi-cam CV   | 4+ streams · 30 fps · edge  | ongoing |
| h2 vtol drone     | on-device CV   | confidential                | 2022→   |
| lorawan fleet     | esp32 · pcb · cloud | field deploy · eu       | 2025    |
| floor visualizer  | sam 2 · homography · web | mvp                | 2026    |
| this readme       | ascii art      | 1 profile · 0 regrets       | today   |

## the manifesto, five lines

```
1. the model is 20% of the work
2. the seam is the other 80%
3. on-device wins when latency, cost, or bandwidth says so
4. three vendors is two too many
5. don't be a hero, be on call
```

## stack, quickly

```yaml
agents:   [LangGraph, Google ADK, MCP, A2A, FastAPI, Postgres]
vision:   [PyTorch, TensorRT, DeepStream, SAM 2, Jetson, Coral]
firmware: [ESP32, STM32, Zephyr, LoRaWAN, BLE, KiCad]
glue:     [Python, C++17, CUDA, Docker, AWS, GCP]
```

## open for

`2-3 day sprints`   `MVPs 4-8 weeks`   `discovery calls`   `second opinions`

## not open for

`staff aug`   `tickets in a queue`   `unpaid trials`   `crypto`

## reach me

```
site      muttequrashi.github.io
linkedin  in/mutte-ur-rahman
email     mutte.rehman [at] vnexia [dot] com
```

<sub>YOLO badge above this readme is a lifestyle, not a bug.</sub>
