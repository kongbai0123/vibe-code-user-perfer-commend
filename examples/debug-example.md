# Example: Debug YOLO Output Mapping Error

## Situation

The model output shows abnormal class IDs such as:

```text
cls_13865
```

Bounding boxes also cover the entire screen incorrectly.

## Recommended Prompt Profiles

Use:

* `core/master_rules.md`
* `profiles/debug_diagnosis.md`
* `profiles/algorithm_ai.md`
* `profiles/edge_deployment.md`

## User Prompt

```text
請套用 debug diagnosis 模式。

我的 YOLO / TFLite 模型在 edge device 上輸出異常：
- class id 出現 cls_13865
- bounding box 橫跨整個畫面
- FPS 很低

請不要直接重寫整個 pipeline。
請先幫我依照 tensor shape、output mapping、confidence decode、bbox decode、NMS、座標縮放順序做系統化診斷。
```

## Expected AI Behavior

The AI should:

1. Check model output tensor shape.
2. Verify whether the output layout is `[N, C]`, `[C, N]`, or another format.
3. Confirm bbox coordinate format (XYWH, XYXY, Center vs Corner).
4. Check class index decoding logic.
5. Check confidence thresholding.
6. Check NMS behavior.
7. Avoid rewriting unrelated code.
8. Provide minimal verification steps (e.g., print tensor values).
