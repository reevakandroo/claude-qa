# TC058: Risk result is strictly one of low, moderate, or high

| Field | Detail |
|-------|--------|
| **Test ID** | TC058 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Complete the full assessment flow with valid patient data |
| 2 | Read the risk result displayed |

## Expected Results

Result value is exactly one of: Low, Moderate, or High. No other value (e.g. "Error", "Unknown", undefined) is shown.

---
*Module: Risk Assessment · Type: Positive*
