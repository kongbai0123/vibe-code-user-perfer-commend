# Vibe Coding Prompt System

A structured prompt profile system for AI-assisted software engineering.

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

```text
AI role mode
+ engineering principles
+ forbidden actions
+ output contract
```

## Prompt Profiles

| File | Purpose |
| --- | --- |
| `core/master_rules.md` | Highest-priority rules and anti-chaos constraints |
| `profiles/vibe_coding.md` | Vibe coding with engineering constraints |
| `profiles/refactor_review.md` | Refactoring and code review |
| `profiles/debug_diagnosis.md` | Systematic debugging and diagnosis |
| `profiles/architecture_design.md` | System architecture design |
| `profiles/algorithm_ai.md` | Algorithm, AI, ML, YOLO, CNN, optical flow |
| `profiles/edge_deployment.md` | Edge deployment, Jetson, embedded systems |
| `profiles/control_system.md` | Control systems and mechatronics safety |
| `profiles/documentation.md` | README, technical docs, research writing |

## Quick Start

For **Vibe Coding**:
```text
Use:
- core/master_rules.md
- profiles/vibe_coding.md
```

For **Debugging**:
```text
Use:
- core/master_rules.md
- profiles/debug_diagnosis.md
```

Check [QUICK_START.md](QUICK_START.md) for more details.

## Recommended Default Rule

Always start with:
```text
core/master_rules.md
```
Then add one task-specific prompt profile.

## License

MIT License.
