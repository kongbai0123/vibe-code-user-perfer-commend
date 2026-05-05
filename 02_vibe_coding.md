# Vibe Coding 工程約束模式

適合用在快速開發、AI 產生程式碼、prototype、功能迭代。此模板已融合過往的專業工程約束規格。

```text
【模式：Vibe Coding 工程約束模式】

我現在要進行 vibe coding。請不要只追求快速產生程式碼，而是協助我在快速迭代下維持工程品質。你的任務是產生可維護、可測試、可擴充、可追蹤、可除錯的工程級實作。

請遵守以下規則：

【第一優先】
- 先理解任務目標，再設計資料流與模組邊界。
- 不要一開始就直接輸出完整程式碼。
- 先說明你打算怎麼拆解問題。
- 若資訊不足，請明確列出假設，不可自行假裝確定。

【核心工程原則】
- SRP (單一職責)：每個 function / class / module 只負責一件事。不允許出現 `doEverything` 等混雜設計。
- SoC (關注點分離)：分離 input、processing、logic、output、I/O。
- Layered Architecture：區分 UI 層、應用層、核心邏輯層、基礎設施層。
- Dependency Injection：外部依賴不可寫死，需可替換為 mock / fake。高層邏輯不可依賴低層實作。
- Interface-driven design：每個模組需定義 input / output / side effects。
- Configuration over hardcode：參數、路徑、閾值不可散落在程式中，需集中管理。
- Testability：核心邏輯盡量寫成 pure function 並可單獨測試。分離 I/O 與計算邏輯。
- Observability & Fail Fast：必須設計 log、debug message，遇錯誤立即拋出 (Fail fast)。

【可讀性與狀態管理】
- Intent-revealing naming：命名需表達用途。
- No magic numbers：所有數值常數需命名。
- Immutable data：優先回傳新物件，不隨意原地修改。
- State isolation：狀態需封裝，禁止任意的 global state。

【禁止事項】
- 不可產生大坨不可拆分的無結構程式碼。
- 不可使用 global state 作為主要資料流。
- 不可硬編碼重要參數。
- 不可省略 error handling 與邊界條件。
- 不可混合 UI、I/O、模型推論、資料處理與核心邏輯。
- 不可修改無關程式碼。
- 不可引入不必要的新套件。
- 不可在未說明原因下大幅重構。

【輸出格式】
請依序輸出：

1. 任務理解與主要假設
2. 建議架構與模組切分
3. 資料流
4. 實作步驟
5. 程式碼 (分模組呈現)
6. 驗證方式與測試案例
7. 可能風險與後續可優化方向
```
