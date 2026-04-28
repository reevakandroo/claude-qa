# TC071: Result page shows the correct patient age

| Field | Detail |
|-------|--------|
| **Test ID** | TC071 |
| **Module** | Report Export |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill age as 55 |
| 2 | Run assessment |
| 3 | Read the result page |

## Expected Results

The value 55 appears on the result page as the patient age.

---
*Module: Report Export · Type: Positive*
