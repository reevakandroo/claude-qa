# TC073: Result page shows the correct patient ID

| Field | Detail |
|-------|--------|
| **Test ID** | TC073 |
| **Module** | Report Export |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill patient ID as PT1001 |
| 2 | Run assessment |
| 3 | Read the result page |

## Expected Results

PT1001 appears on the result page, confirming the correct patient record.

---
*Module: Report Export · Type: Positive*
