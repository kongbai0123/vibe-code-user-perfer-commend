# Vibe Coding Prompt System

A structured prompt profile system for AI-assisted software engineering, debugging, refactoring, architecture design, AI experiments, edge deployment, control systems, and technical documentation.

## Why This Repository Exists

Most AI coding prompts focus only on speed.

This repository focuses on **controlled speed**:

```text
fast iteration
+ engineering constraints
+ validation
+ traceability
+ minimal-change discipline
```

## Core Concept

The fundamental formula for high-quality AI interaction:

```text
AI role mode
+ engineering principles
+ forbidden actions
+ output contract
```

## Prompt Profiles

| File Path | Purpose |
| :--- | :--- |
| `core/master_rules.md` | **Highest-priority** rules and anti-chaos constraints |
| `profiles/vibe_coding.md` | Vibe coding with professional engineering constraints |
| `profiles/refactor_review.md` | Expert-level code refactoring and professional review |
| `profiles/debug_diagnosis.md` | Systematic debugging and root-cause diagnosis |
| `profiles/architecture_design.md` | System architecture and modular design |
| `profiles/algorithm_ai.md` | Algorithm design, AI, ML, YOLO, CNN, Optical Flow |
| `profiles/edge_deployment.md` | Edge deployment, Jetson, TensorRT, TFLite, FPS/Latency |
| `profiles/control_system.md` | Control systems, Mechatronics safety, Stability analysis |
| `profiles/documentation.md` | README, technical documentation, research writing |

## Quick Start

### For Vibe Coding (Rapid Feature Implementation):

**Use:**
- `core/master_rules.md`
- `profiles/vibe_coding.md`

**Then ask:**
```text
請套用 vibe coding 工程約束模式。
任務如下：
...
```

### For Debugging (Systematic Diagnosis):

**Use:**
- `core/master_rules.md`
- `profiles/debug_diagnosis.md`

### For Architecture Design:

**Use:**
- `core/master_rules.md`
- `profiles/architecture_design.md`

## Recommended Default Rule

Always start with `core/master_rules.md`, then add one task-specific prompt profile from the `profiles/` folder. Check out the [PROMPT_INDEX.md](PROMPT_INDEX.md) for more combinations.

## License

MIT License.
