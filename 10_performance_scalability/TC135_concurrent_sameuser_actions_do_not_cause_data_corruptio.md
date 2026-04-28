# TC135: Concurrent same-user actions do not cause data corruption

| Field | Detail |
|-------|--------|
| **Test ID** | TC135 |
| **Module** | Performance & Scalability |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open the app in two separate browser tabs with the same account |
| 2 | Fill and submit patient forms in both tabs simultaneously |
| 3 | Check results |

## Expected Results

Both assessments complete independently. No data from Tab A appears in Tab B result. No crash.

---
*Module: Performance & Scalability · Type: Edge*
