# TC012: Multiple failed logins do not crash the app — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC012 |
| **Module** | Authentication |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Attempt login with wrong credentials 5 times in succession |
| 2 | After each failed attempt observe app state |
| 3 | Attempt a valid login after the 5 failures |

## Expected Results

App remains responsive after all failed attempts. No crash, freeze, or error 500. Valid login still works after repeated failures.

---
*Module: Authentication · Type: Edge*
