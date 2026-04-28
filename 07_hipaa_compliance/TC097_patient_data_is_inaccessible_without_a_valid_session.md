# TC097: Patient data is inaccessible without a valid session

| Field | Detail |
|-------|--------|
| **Test ID** | TC097 |
| **Module** | HIPAA Compliance |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC008**](../00_preconditions/PC008_no_active_session.md) — No user is logged in; browser has no valid session

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open a fresh browser window (private/incognito) |
| 2 | Navigate directly to the ECG dashboard URL |
| 3 | Observe what content loads |

## Expected Results

No ECG records or patient data are visible. User is redirected to login. PHI is fully protected behind authentication.

---
*Module: HIPAA Compliance · Type: Negative*
