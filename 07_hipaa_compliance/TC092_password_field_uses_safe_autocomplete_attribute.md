# TC092: Password field uses safe autocomplete attribute

| Field | Detail |
|-------|--------|
| **Test ID** | TC092 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC001**](../00_preconditions/PC001_app_loaded_at_login_url.md) — App is open at the login page; no user is logged in

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open login page |
| 2 | Inspect the autocomplete attribute on the password field |

## Expected Results

Autocomplete is set to "off", "current-password", or "new-password". Browser does not store the password without explicit consent.

---
*Module: HIPAA Compliance · Type: Positive*
