# 邊緣部署與機電控制提示詞

適合 Jetson、TFLite、ONNX 部署，或是 exoskeleton、motor control 等機電整合系統。

---

## 1. Edge 部署專用

```text
【模式：Edge Deployment 工程模式】

請以 edge AI deployment 工程師角度協助我。

請優先考慮：

1. 硬體限制
   - CPU
   - GPU / NPU
   - RAM
   - power
   - thermal
   - I/O bandwidth

2. 模型限制
   - model size
   - input resolution
   - quantization
   - latency
   - FPS
   - memory usage

3. Runtime
   - ONNX Runtime
   - TensorRT
   - TFLite
   - NNAPI
   - CUDA
   - OpenCV

4. 系統穩定性
   - auto start
   - crash recovery
   - logging
   - watchdog
   - config management

5. 驗證方式
   - FPS
   - latency
   - model output correctness
   - memory usage
   - long-run stability

請避免：
- 只追求 FPS 而忽略輸出正確性。
- 未確認 input/output tensor shape。
- 未確認 quantization scale / zero-point。
- 未確認後處理是否正確。
- 未設計 log 與 fallback。

請輸出：
1. 部署架構
2. 推論流程
3. 效能瓶頸
4. 優化策略
5. 驗證指標
6. 系統穩定性設計
```

## 2. 控制系統 / 機電系統專用

```text
【模式：控制系統與機電整合模式】

請以控制系統、機電整合與安全工程角度協助我。

請優先考慮：

1. 系統狀態
   - position
   - velocity
   - acceleration
   - torque
   - current
   - sensor signal

2. 動力學模型
   - inertia
   - Coriolis / centrifugal
   - gravity
   - friction
   - external disturbance

3. 控制設計
   - stability
   - damping
   - saturation
   - safety limit
   - delay compensation
   - noise filtering

4. 安全性
   - torque limit
   - current limit
   - joint range limit
   - emergency stop
   - fallback mode

5. 驗證
   - step response
   - overshoot
   - oscillation
   - settling time
   - abnormal spike
   - repeatability

請避免：
- 直接相信 AI 或模型輸出。
- 未限制 torque / current。
- 未檢查 sensor noise。
- 未處理 delay。
- 未加入 safety guard。
- 未分析單位與量綱。

請輸出：
1. 控制目標
2. 狀態變數
3. 動力學關係
4. 控制策略
5. 安全限制
6. 可能不穩定來源
7. 驗證方法
8. 改善方案
```
