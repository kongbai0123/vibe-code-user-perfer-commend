# Vibe Coding Prompt System

A structured prompt profile system for AI-assisted software engineering.

## Why this exists

Most AI coding prompts focus only on speed.
This repository focuses on **controlled speed**:

- **Fast Iteration**: Rapid prototype generation without sacrificing quality.
- **Architecture Constraints**: Enforces SRP, SoC, and Layered Architecture.
- **Validation**: Every change must be verified and logged.
- **Debugging**: Systematic diagnosis over guessing.
- **Traceability**: All model decisions must be traceable to a config or source.
- **Minimal-Change Discipline**: No random refactoring or unrelated changes.

## Core Concept

The fundamental formula for high-quality AI interaction:
```text
AI role mode
+ engineering principles
+ forbidden actions
+ output contract
```

## Quick Start

### For Vibe Coding (Rapid Development)

1. Use `core/01_master_rules.md`.
2. Use `profiles/vibe_coding.md`.

Then ask:
```text
請套用 vibe coding 模式。
任務如下：
[您的任務描述]
```

Check out the [QUICK_START.md](QUICK_START.md) for more details.

## Prompt Profiles Index

| Profile | File | Use case |
| --- | --- | --- |
| **Master Rules** | `core/01_master_rules.md` | Highest-priority rules for all tasks |
| **Vibe Coding** | `profiles/vibe_coding.md` | Fast AI-assisted coding & prototyping |
| **Refactor & Review** | `profiles/refactor_review.md` | Code refactoring & expert review |
| **Debug Diagnosis** | `profiles/debug_diagnosis.md` | Systematic bug diagnosis & fixing |
| **Architecture Design** | `profiles/architecture_design.md` | System architecture & module design |
| **Algorithm & AI** | `profiles/algorithm_ai.md` | AI / ML / Algorithm research & design |
| **Edge Deployment** | `profiles/edge_deployment.md` | Jetson / TFLite / ONNX edge deployment |
| **Control System** | `profiles/control_system.md` | Control system & Mechatronics safety |
| **Documentation** | `profiles/documentation.md` | README / Paper / Technical docs |

## Folder Structure

- `core/`: Fundamental rules (Master Rules, Execution Gate, Minimal Change Policy).
- `profiles/`: Specific scenario prompts (Vibe Coding, Debug, AI, Edge, etc.).
- `recipes/`: Pre-combined prompt packs for quick use.
- `examples/`: Real-world usage scenarios and expected AI behavior.
- `tool-specific/`: Configurations for Cursor, Copilot, Claude Code, and Windsurf.

## License

MIT License.
