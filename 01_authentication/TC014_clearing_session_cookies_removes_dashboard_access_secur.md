# TC014: Clearing session cookies removes dashboard access — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC014 |
| **Module** | Authentication |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Login successfully |
| 2 | Open browser dev tools |
| 3 | Clear all cookies and local storage |
| 4 | Reload the page |
| 5 | Observe what loads |

## Expected Results

User is redirected to login page. Dashboard is no longer accessible. Session is properly invalidated.

---
*Module: Authentication · Type: Edge*
