# TC016: ECG list loads after successful login

| Field | Detail |
|-------|--------|
| **Test ID** | TC016 |
| **Module** | ECG Dashboard |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to login page |
| 2 | Enter valid credentials |
| 3 | Click Login |
| 4 | Wait for dashboard to load |
| 5 | Observe ECG list |

## Expected Results

ECG list is displayed with one or more ECG entries visible. No blank screen or loading spinner stuck.

---
*Module: ECG Dashboard · Type: Positive*
