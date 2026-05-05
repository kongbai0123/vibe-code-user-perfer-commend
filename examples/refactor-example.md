# Example: Project Refactoring

## Situation
I have a 500-line Python file with mixed logic, UI, and database calls. I want to modularize it.

## Recommended Prompt Profiles
- `core/01_master_rules.md`
- `profiles/refactor_review.md`

## User Prompt
```text
請套用 refactor review 模式，重構層級設定為 Level 3。
以下是我的程式碼：
[Code...]
```

## Expected AI Behavior
1. Analyze the current violations (SRP, SoC).
2. Identify modules to be extracted.
3. Propose a layered architecture (UI, Logic, DB).
4. Refactor without changing the original behavior.
5. Provide a summary of changes and a test plan.
