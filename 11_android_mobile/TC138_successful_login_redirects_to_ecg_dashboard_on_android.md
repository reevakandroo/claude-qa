# TC138: Successful login redirects to ECG dashboard on Android

| Field | Detail |
|-------|--------|
| **Test ID** | TC138 |
| **Module** | Android Mobile |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in
- [**PC002**](../00_preconditions/PC002_valid_user_credentials.md) — A valid registered user account exists with known credentials

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter valid credentials on Android viewport |
| 2 | Tap Login |
| 3 | Wait for redirect |

## Expected Results

User is redirected to the ECG dashboard. URL shows #/ecgs. ECG list begins loading.

---
*Module: Android Mobile · Type: Positive*
