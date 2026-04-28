# TC004: Empty email field prevents login

| Field | Detail |
|-------|--------|
| **Test ID** | TC004 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Leave the email field completely empty |
| 3 | Enter a valid password |
| 4 | Click Login |

## Expected Results

Login is not submitted. App stays on login page. Email field shows required error or button stays disabled.

---
*Module: Authentication · Type: Negative*
