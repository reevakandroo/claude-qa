# TC098: Result page contains patient ID for audit traceability

| Field | Detail |
|-------|--------|
| **Test ID** | TC098 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter Patient ID: PT-TRACE-01 |
| 2 | Run full risk assessment |
| 3 | Read result page |

## Expected Results

PT-TRACE-01 is visible on the result page. Every assessment result is traceable to a specific patient record.

---
*Module: HIPAA Compliance · Type: Positive*
