# TC072: Result page shows the correct patient gender

| Field | Detail |
|-------|--------|
| **Test ID** | TC072 |
| **Module** | Report Export |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill gender as Male |
| 2 | Run assessment |
| 3 | Read the result page |

## Expected Results

The word "Male" appears on the result page.

---
*Module: Report Export · Type: Positive*
