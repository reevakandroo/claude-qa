# TC125: Login page loads within 15 seconds on standard connection

| Field | Detail |
|-------|--------|
| **Test ID** | TC125 |
| **Module** | Performance & Scalability |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- Browser is open. Standard broadband connection (10 Mbps+).

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Start a timer |
| 2 | Navigate to the login URL |
| 3 | Wait until the login form is fully interactive |
| 4 | Stop timer |

## Expected Results

Login form is ready for input within 15 seconds. Flutter canvas has loaded.

---
*Module: Performance & Scalability · Type: Positive*
