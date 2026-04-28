# TC126: ECG dashboard list renders within 15 seconds after login

| Field | Detail |
|-------|--------|
| **Test ID** | TC126 |
| **Module** | Performance & Scalability |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- User has just clicked Login.

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Start a timer at the moment Login is clicked |
| 2 | Wait until the first ECG entry appears in the list |
| 3 | Stop timer |

## Expected Results

ECG list is visible within 15 seconds. No spinner is stuck.

---
*Module: Performance & Scalability · Type: Positive*
