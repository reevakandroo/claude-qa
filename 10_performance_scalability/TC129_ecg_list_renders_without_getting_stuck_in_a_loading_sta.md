# TC129: ECG list renders without getting stuck in a loading state

| Field | Detail |
|-------|--------|
| **Test ID** | TC129 |
| **Module** | Performance & Scalability |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in |
| 2 | Wait up to 20 seconds |
| 3 | Check whether ECG entries appear or a spinner runs indefinitely |

## Expected Results

ECG entries appear on screen within 20 seconds. No infinite loading spinner.

---
*Module: Performance & Scalability · Type: Positive*
