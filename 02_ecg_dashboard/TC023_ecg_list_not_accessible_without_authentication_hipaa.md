# TC023: ECG list not accessible without authentication — HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC023 |
| **Module** | ECG Dashboard |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC008**](../00_preconditions/PC008_no_active_session.md) — No user is logged in; browser has no valid session

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Ensure no user is logged in |
| 2 | Navigate directly to #/ecgs URL |
| 3 | Observe the page content |

## Expected Results

ECG records are NOT displayed. User is redirected to login or shown an access-denied message. No PHI visible.

---
*Module: ECG Dashboard · Type: Negative*
