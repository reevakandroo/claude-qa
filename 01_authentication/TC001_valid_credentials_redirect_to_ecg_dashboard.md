# TC001: Valid credentials redirect to ECG dashboard

| Field | Detail |
|-------|--------|
| **Test ID** | TC001 |
| **Module** | Authentication |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in
- [**PC002**](../00_preconditions/PC002_valid_user_credentials.md) — A valid registered user account exists with known credentials

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to the login page |
| 2 | Enter registered email: reeva.kandroo@tricog.com |
| 3 | Enter correct password: Tricog@1234 |
| 4 | Click the Login button |

## Expected Results

User is authenticated and redirected to the ECG dashboard (#/ecgs). No error message is shown.

---
*Module: Authentication · Type: Positive*
