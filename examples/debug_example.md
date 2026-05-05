# Example: 錯誤診斷 (Debug Diagnosis)

## 情境描述
我的 Python 程式在載入 TensorRT 模型時報錯：`Error Code 1: Internal Error (Could not find a layer...)`。

## 使用 Profile
- `core/master_rules.md`
- `profiles/debug_diagnosis.md`

## 預期 AI 行為
1. 先要求確認 TensorRT 版本與硬體相容性。
2. 分析是否為版本不一致或路徑錯誤。
3. 建議檢查 `trtexec` 的輸出。
4. 提供分層診斷步驟 (環境 -> 模型 -> 程式碼)。
