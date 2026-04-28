# TC096: Login error messages do not reveal patient account details

| Field | Detail |
|-------|--------|
| **Test ID** | TC096 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Attempt login with a wrong email |
| 2 | Read the error message |
| 3 | Attempt login with a valid email but wrong password |
| 4 | Compare both error messages |

## Expected Results

Error messages are generic (e.g. "Invalid credentials"). Neither message reveals patient names, IDs, or whether an account exists.

---
*Module: HIPAA Compliance · Type: Positive*
