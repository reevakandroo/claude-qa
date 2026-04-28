# TC010: Very long email (256+ characters) is rejected or handled safely

| Field | Detail |
|-------|--------|
| **Test ID** | TC010 |
| **Module** | Authentication |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter an email of 256+ characters (e.g. aaa...@ex.com) |
| 2 | Enter a valid password |
| 3 | Click Login |
| 4 | Observe result |

## Expected Results

App either shows an input length error or rejects the login gracefully. App does not crash.

---
*Module: Authentication · Type: Edge*
