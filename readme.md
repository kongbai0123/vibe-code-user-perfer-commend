# Vibe Coding Prompt System

A structured prompt profile system for AI-assisted software engineering.

This repository is designed for developers who use AI coding tools but still need engineering discipline, maintainability, debugging capability, and reproducibility.

## Core Concept

Most AI coding prompts optimize for speed.

This repository optimizes for controlled speed:

```text
fast iteration
+ architectural constraints
+ validation
+ traceability
+ minimal-change discipline
```

## When to Use

Use this repository when you want AI to help with:

* vibe coding
* debugging
* refactoring
* architecture design
* AI / ML experiment planning
* edge deployment
* control system engineering
* technical documentation
* research writing

## Quick Start

### For vibe coding

Copy:
- `core/01_master_rules.md`
- `profiles/vibe_coding.md`

Then ask:

```text
請套用 vibe coding 模式。任務如下：
...
```

## Directory Structure

- `core/`: 核心基礎規則 (Master Rules, Execution Gate, 最小變更原則)
- `profiles/`: 情境式提示詞 (Vibe Coding, Debug, 重構, 架構, AI, Edge 等)
- `recipes/`: 常用組合包 (快速寫功能、修 Bug 等)
- `examples/`: 實際使用範例
- `tool-specific/`: 針對 Cursor、Copilot 等 AI IDE 的設定檔

請查看 [PROMPT_INDEX.md](PROMPT_INDEX.md) 來決定你要使用哪個 Prompt Profile。
