# TC084: Brute force login attempts do not expose user account info

| Field | Detail |
|-------|--------|
| **Test ID** | TC084 |
| **Module** | Security |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Try logging in with correct email but wrong passwords 10 times |
| 2 | Read each error message |
| 3 | Note whether messages differ for valid vs invalid emails |

## Expected Results

All failed login attempts show the same generic error. The system does not reveal whether an email exists or not.

---
*Module: Security · Type: Edge*
