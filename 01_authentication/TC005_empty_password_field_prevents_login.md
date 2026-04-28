# TC005: Empty password field prevents login

| Field | Detail |
|-------|--------|
| **Test ID** | TC005 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Enter a valid email |
| 3 | Leave the password field completely empty |
| 4 | Click Login |

## Expected Results

Login is not submitted. App stays on login page. Password field shows required error or button stays disabled.

---
*Module: Authentication · Type: Negative*
