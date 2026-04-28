# TC021: ECG list loads within 15 seconds — Performance

| Field | Detail |
|-------|--------|
| **Test ID** | TC021 |
| **Module** | ECG Dashboard |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Start a timer immediately after clicking Login |
| 2 | Wait for the ECG list to appear on screen |
| 3 | Stop the timer when the first ECG entry is visible |

## Expected Results

ECG list is fully visible within 15 seconds of login. No stuck spinner.

---
*Module: ECG Dashboard · Type: Positive*
