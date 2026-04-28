# TC070: Result page shows the correct patient name

| Field | Detail |
|-------|--------|
| **Test ID** | TC070 |
| **Module** | Report Export |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill patient name as John Doe |
| 2 | Run assessment |
| 3 | Read the result page content |

## Expected Results

The text "John Doe" appears on the result page. Name is correctly carried forward from the form.

---
*Module: Report Export · Type: Positive*
