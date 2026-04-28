# TC068: No server error messages or stack traces shown to user — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC068 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill valid patient data |
| 2 | Click Get Risk Assessment |
| 3 | Read the result screen content carefully |

## Expected Results

No technical error messages, stack traces, file paths, or exception details are visible to the user. Only the risk result or a friendly error is shown.

---
*Module: Risk Assessment · Type: Positive*
