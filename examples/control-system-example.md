# Example: Exoskeleton Control System

## Situation
Designing a torque control loop for a knee exoskeleton. Noticed oscillations during high-speed movement.

## Recommended Prompt Profiles
- `core/01_master_rules.md`
- `profiles/control_system.md`

## User Prompt
```text
請套用控制系統與機電整合模式。
我的膝蓋外骨骼在高速運動時出現震盪，請分析穩定性並提供修正方案。
```

## Expected AI Behavior
1. Analyze the dynamic model (inertia, friction).
2. Check for sensor noise and delay in the loop.
3. Analyze PID/PD gain margins.
4. Suggest safety limits (torque saturation).
5. Design a step response test to verify stability.
