# TC078: Exported result page contains patient identifier for audit trail — HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC078 |
| **Module** | Report Export |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter unique patient ID: PT-AUDIT99 |
| 2 | Run full assessment |
| 3 | Read the result page |
| 4 | Confirm patient ID is visible |

## Expected Results

Patient ID PT-AUDIT99 is visible on the result page. The record is traceable to this specific patient.

---
*Module: Report Export · Type: Positive*
