# Example: YOLO Training Experiment

## Situation
I am training a YOLOv8 model for road obstacle detection. The mAP is high but it fails on small objects.

## Recommended Prompt Profiles
- `core/01_master_rules.md`
- `profiles/algorithm_ai.md`

## User Prompt
```text
請套用 AI 模型訓練與實驗設計模式，任務類型為 Detection。
目前遇到了小物件偵測率低的問題，請分析原因並設計實驗。
```

## Expected AI Behavior
1. Check data distribution for small objects.
2. Suggest image augmentation strategies (mosaic, mixup).
3. Recommend hyperparameter tuning (box loss, gain).
4. Suggest model architectural changes (input size, backbone).
5. Define tracking metrics (mAP@small).
