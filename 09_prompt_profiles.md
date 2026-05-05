# 推薦常用組合與 Prompt Profile

提供日常開發中最推薦的 prompt 搭配組合，以及極簡版萬用提示詞。

---

## 1. 最推薦的「常用組合」

你可以將不同的原則疊加使用，達成不同的工作目標：

### A. 快速寫功能
```text
最高優先級工作規則 + Vibe Coding 工程約束模式 + Execution Gate + 最小變更原則
```

### B. 修 Bug
```text
最高優先級工作規則 + Debug 診斷模式 + 最小變更原則
```

### C. 重構專案
```text
最高優先級工作規則 + Code Refactor 審查與重構模式 + Code Review 專業審查模式
```

### D. 設計新系統
```text
最高優先級工作規則 + 系統架構設計模式 + 工程原則總表
```

### E. AI 模型訓練
```text
最高優先級工作規則 + AI 模型訓練與實驗設計模式 + Experiment Tracking 要求
```

---

## 2. 建立 Prompt Profile 指令清單

你可以利用這個列表，在對話前加上斜線指令，告知 AI 使用哪個設定檔：

- `/prompt-vibe-code` (參見 `02_vibe_coding.md`)
- `/prompt-debug` (參見 `04_debug_diagnosis.md`)
- `/prompt-refactor` (參見 `03_refactor_and_review.md`)
- `/prompt-architecture` (參見 `05_architecture_design.md`)
- `/prompt-edge-deploy` (參見 `07_edge_and_control.md` 下)
- `/prompt-ai-training` (參見 `06_algorithm_and_ai.md` 下)
- `/prompt-control-system` (參見 `07_edge_and_control.md` 下)
- `/prompt-paper-writing` (參見 `08_documentation.md` 上)
- `/prompt-readme` (參見 `08_documentation.md` 下)

**用法範例**：
> 請套用 `/prompt-vibe-code` 模式。
> 任務如下：...

---

## 3. 最實用的極簡版萬用提示詞

如果你只想要一段通用提示詞，可以直接用這個：

```text
請以資深工程師與架構審查者角度協助我。

本次任務請遵守：

1. 先分析，不要直接開寫。
2. 明確定義 input / output / data flow。
3. 遵守 SRP、SoC、Layered Architecture、Dependency Injection。
4. 不可使用 global state 作為主要資料流。
5. 不可硬編碼重要參數。
6. 核心邏輯需可測試。
7. 必須加入錯誤處理、log、sanity check。
8. 不可修改無關程式碼。
9. 若資訊不足，請標註假設。
10. 最後提供驗證方式與風險分析。

請依序輸出：
1. 任務理解
2. 設計方案
3. 資料流
4. 實作
5. 測試方式
6. 風險與注意事項
```
