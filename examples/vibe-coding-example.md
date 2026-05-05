# Example: Vibe Coding Implementation

## Situation
I want to implement a simple Python cache decorator with TTL (Time To Live).

## Recommended Prompt Profiles
- `core/master_rules.md`
- `profiles/vibe_coding.md`

## User Prompt
```text
請套用 vibe coding 工程約束模式。

任務如下：
請幫我實作一個具備 TTL 功能的 Python 快取裝飾器。
```

## Expected AI Behavior
1. Check requirements (LRU needed? Thread safety?).
2. Design the data flow (Input -> Key Hash -> TTL Check -> Return/Compute).
3. Implement using a layered approach (Cache Logic separated from Decorator).
4. Provide unit tests.
5. Provide structured logs.
