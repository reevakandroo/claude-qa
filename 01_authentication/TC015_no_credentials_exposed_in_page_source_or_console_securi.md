# TC015: No credentials exposed in page source or console — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC015 |
| **Module** | Authentication |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Navigate to login page |
| 2 | Open browser dev tools > Console |
| 3 | Open dev tools > Sources and inspect page source |
| 4 | Search for the password string |

## Expected Results

Password "Tricog@1234" is not visible in page source, console logs, or network request payloads in plain text.

---
*Module: Authentication · Type: Positive*
