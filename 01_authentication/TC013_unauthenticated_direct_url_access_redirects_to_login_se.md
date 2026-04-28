# TC013: Unauthenticated direct URL access redirects to login — Security / HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC013 |
| **Module** | Authentication |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC008**](../00_preconditions/PC008_no_active_session.md) — No user is logged in; browser has no valid session

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open a new browser tab |
| 2 | Navigate directly to https://cardiocheck-uat.up.railway.app/#/ecgs without logging in |
| 3 | Observe what loads |

## Expected Results

App redirects user to login page. Patient ECG list is NOT visible. No PHI is exposed to unauthenticated users.

---
*Module: Authentication · Type: Negative*
