# TC011: Password field is masked (type=password) — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC011 |
| **Module** | Authentication |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Inspect the password input element using browser dev tools |
| 3 | Check the input type attribute |

## Expected Results

Password input type is "password". Characters are masked and not visible in plain text.

---
*Module: Authentication · Type: Positive*
