# TC006: Both fields empty prevent login

| Field | Detail |
|-------|--------|
| **Test ID** | TC006 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Leave both email and password fields empty |
| 3 | Click Login |

## Expected Results

Login is not triggered. App stays on login page. No crash or redirect occurs.

---
*Module: Authentication · Type: Negative*
