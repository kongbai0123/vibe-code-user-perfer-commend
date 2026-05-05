# Prompt Index

This file helps you choose the correct prompt profile for different AI-assisted engineering tasks.

## Quick Selection Table

| Situation | Recommended Prompt Files |
| :--- | :--- |
| **快速開發新功能** | `core/master_rules.md` + `profiles/vibe_coding.md` |
| **修 Bug / 錯誤診斷** | `core/master_rules.md` + `profiles/debug_diagnosis.md` |
| **重構既有程式碼** | `core/master_rules.md` + `profiles/refactor_review.md` |
| **Code Review** | `core/master_rules.md` + `profiles/refactor_review.md` |
| **設計新系統架構** | `core/master_rules.md` + `profiles/architecture_design.md` |
| **設計 AI / ML 實驗** | `core/master_rules.md` + `profiles/algorithm_ai.md` |
| **YOLO / CNN / 任務** | `core/master_rules.md` + `profiles/algorithm_ai.md` |
| **Jetson / Edge 部署** | `core/master_rules.md` + `profiles/edge_deployment.md` |
| **控制系統 / 機電整合** | `core/master_rules.md` + `profiles/control_system.md` |
| **寫 README / 技術文件** | `core/master_rules.md` + `profiles/documentation.md` |
| **論文 / 研究紀錄撰寫** | `profiles/documentation.md` |

## Default Usage Pattern

For most tasks, use:

```text
core/master_rules.md
+
任務對應的專用 prompt profile (in profiles/ folder)
```

### Example

> 「請套用以下 prompt profiles：
> - `core/master_rules.md`
> - `profiles/vibe_coding.md`
> 
> 任務如下：
> 請協助我建立一個 Python inference pipeline。」
