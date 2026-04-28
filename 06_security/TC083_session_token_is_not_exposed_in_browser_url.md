# TC083: Session token is not exposed in browser URL

| Field | Detail |
|-------|--------|
| **Test ID** | TC083 |
| **Module** | Security |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC003**](../00_preconditions/PC003_user_logged_in_dashboard.md) — User is authenticated and the ECG dashboard is displayed

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in successfully |
| 2 | Inspect the browser address bar |
| 3 | Check if any auth token or session ID appears in the URL |

## Expected Results

No authentication token, session ID, or credentials appear in the URL. Tokens are stored in cookies or memory only.

---
*Module: Security · Type: Positive*
