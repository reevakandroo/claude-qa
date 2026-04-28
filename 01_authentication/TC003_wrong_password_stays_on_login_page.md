# TC003: Wrong password stays on login page

| Field | Detail |
|-------|--------|
| **Test ID** | TC003 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in
- [**PC002**](../00_preconditions/PC002_valid_user_credentials.md) — A valid registered user account exists with known credentials

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Enter valid email |
| 3 | Enter incorrect password: WrongPass999! |
| 4 | Click Login |

## Expected Results

Login fails. App stays on login page or shows an authentication error. No dashboard access granted.

---
*Module: Authentication · Type: Negative*
