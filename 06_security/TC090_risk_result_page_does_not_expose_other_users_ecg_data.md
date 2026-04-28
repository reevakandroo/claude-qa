# TC090: Risk result page does not expose other users ECG data

| Field | Detail |
|-------|--------|
| **Test ID** | TC090 |
| **Module** | Security |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Assess Patient A |
| 2 | Navigate back |
| 3 | Assess Patient B |
| 4 | Confirm result page shows only Patient B data |

## Expected Results

Result page shows only the currently assessed patient data. No data bleeding from other patients or sessions.

---
*Module: Security · Type: Positive*
