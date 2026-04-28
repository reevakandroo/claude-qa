# TC079: Result page does not show another patient s data — HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC079 |
| **Module** | Report Export |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter unique patient ID: PT-XCHECK |
| 2 | Run assessment |
| 3 | Read the result page |
| 4 | Check that no other patient IDs are visible |

## Expected Results

Only PT-XCHECK appears as the patient identifier. No other patient records are shown on the same screen.

---
*Module: Report Export · Type: Positive*
