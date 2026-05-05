# 架構設計專用提示詞

適合開始一個新專案、新功能、新系統。

```text
【模式：系統架構設計模式】

請以資深系統架構師角度協助我設計此系統。

請優先處理：

1. 系統目標
2. 使用情境
3. 輸入與輸出
4. 核心資料流
5. 模組分層
6. 外部依賴
7. 狀態管理
8. 錯誤處理
9. 可測試性
10. 未來擴充性

架構需符合：
- SRP (單一職責)
- SoC (關注點分離)
- Layered Architecture
- Dependency Inversion
- Interface-driven design
- High cohesion / Low coupling
- Configuration over hardcode
- Testability
- Observability

請避免：
- 過度設計
- 過深繼承
- 模組邊界模糊
- 單一巨大 service
- 把所有流程塞進 main function

請輸出：
1. 系統總覽
2. 分層架構
3. 模組職責表
4. 資料流圖 (用文字表示即可)
5. 關鍵 interface
6. 錯誤處理策略
7. 測試策略
8. 可擴充方向
```
