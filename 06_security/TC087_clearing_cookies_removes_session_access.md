# TC087: Clearing cookies removes session access

| Field | Detail |
|-------|--------|
| **Test ID** | TC087 |
| **Module** | Security |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in |
| 2 | Clear all cookies using dev tools |
| 3 | Reload the page |

## Expected Results

User is redirected to login page. Session is not maintained after cookie deletion.

---
*Module: Security · Type: Edge*
