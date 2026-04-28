# TC082: Unauthenticated navigation to dashboard is blocked

| Field | Detail |
|-------|--------|
| **Test ID** | TC082 |
| **Module** | Security |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC008**](../00_preconditions/PC008_no_active_session.md) — No user is logged in; browser has no valid session

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Ensure no user is logged in |
| 2 | Navigate directly to #/ecgs URL |
| 3 | Observe what the page displays |

## Expected Results

App does NOT show the ECG list. User is redirected to login page or shown an access denied screen. No PHI visible.

---
*Module: Security · Type: Negative*
