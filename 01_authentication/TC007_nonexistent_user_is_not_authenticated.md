# TC007: Non-existent user is not authenticated

| Field | Detail |
|-------|--------|
| **Test ID** | TC007 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Enter unregistered email: ghost@nowhere.com |
| 3 | Enter any password |
| 4 | Click Login |
| 5 | Wait for response |

## Expected Results

Login fails. App stays on login page or shows user-not-found error. No dashboard access granted.

---
*Module: Authentication · Type: Negative*
