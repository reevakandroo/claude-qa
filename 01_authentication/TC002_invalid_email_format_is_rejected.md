# TC002: Invalid email format is rejected

| Field | Detail |
|-------|--------|
| **Test ID** | TC002 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Enter malformed email: "invalidemail" (no @ symbol) |
| 3 | Enter any password |
| 4 | Click Login |

## Expected Results

App stays on the login page or shows a validation error. User is NOT redirected to the dashboard.

---
*Module: Authentication · Type: Negative*
