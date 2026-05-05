# Example: Jetson Nano Deployment

## Situation
Deploying a real-time detection model on Jetson Nano using TensorRT. FPS is below 10.

## Recommended Prompt Profiles
- `core/01_master_rules.md`
- `profiles/edge_deployment.md`

## User Prompt
```text
請套用 Edge Deployment 工程模式。
我在 Jetson Nano 上使用 TensorRT 推論，FPS 只有 8，需要優化。
```

## Expected AI Behavior
1. Analyze bottlenecks (Memory bandwidth vs Computation).
2. Check quantization settings (INT8 vs FP16).
3. Analyze Pre-processing/Post-processing overhead on CPU.
4. Suggest TensorRT engine optimization profiles.
5. Propose a validation plan for accuracy vs speed.
