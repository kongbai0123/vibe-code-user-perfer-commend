# Quick Start

This repository provides reusable prompt profiles for AI-assisted engineering work.

## Basic Usage

1. **Choose your task type**: Check the [PROMPT_INDEX.md](PROMPT_INDEX.md).
2. **Combine and Copy**: Most tasks require `core/master_rules.md` plus a specific profile.
3. **Paste**: Input the prompt content into your AI assistant.
4. **Run**: Add your actual task below the prompt.

## Example: Vibe Coding

Use:
- `core/master_rules.md`
- `profiles/vibe_coding.md`

Prompt:
```text
請套用 vibe coding 工程約束模式。

任務如下：
請幫我實作一個影像輸入、模型推論、後處理與結果輸出的 Python pipeline。
```

## Example: Debugging

Use:
- `core/master_rules.md`
- `profiles/debug_diagnosis.md`

Prompt:
```text
請套用 debug diagnosis 模式。

以下是錯誤訊息與程式碼：
...
```

## Example: Edge Deployment

Use:
- `core/master_rules.md`
- `profiles/edge_deployment.md`

Prompt:
```text
請套用 edge deployment 工程模式。

目標平台：Jetson Orin Nano
任務：將 YOLO 模型部署成開機自動啟動的推論系統。
```
