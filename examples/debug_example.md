# Example: Debug 診斷實作

## 情境描述
YOLO 模型在 Jetson 上跑出的 BBox 座標嚴重偏移。

## 使用 Profile
- `core/01_master_rules.md`
- `profiles/debug_diagnosis.md`
- `profiles/edge_deployment.md`

## 預期 AI 行為
1. 分析是否為 Tensor Mapping 問題。
2. 檢查座標格式 (Normalized vs Pixel)。
3. 確認 Pre-processing 與 Post-processing 是否一致。
4. 提供診斷步驟而非直接給一段新的 Code。
