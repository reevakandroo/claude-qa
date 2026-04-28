# TC008: SQL injection in credentials does not bypass login

| Field | Detail |
|-------|--------|
| **Test ID** | TC008 |
| **Module** | Authentication |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter SQL injection payload in email: ' OR '1'='1 |
| 2 | Enter same payload in password |
| 3 | Click Login |
| 4 | Observe result |

## Expected Results

Login is rejected. App stays on login page. Database is not exposed. No data leak in error messages.

---
*Module: Authentication · Type: Edge*
