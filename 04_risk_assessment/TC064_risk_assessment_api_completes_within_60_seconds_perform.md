# TC064: Risk assessment API completes within 60 seconds — Performance

| Field | Detail |
|-------|--------|
| **Test ID** | TC064 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill valid patient form |
| 2 | Start a stopwatch |
| 3 | Click Get Risk Assessment |
| 4 | Stop timer when result appears on screen |

## Expected Results

Risk result appears within 60 seconds. If it exceeds 60 seconds, a loading indicator must be shown and the UI must not freeze.

---
*Module: Risk Assessment · Type: Positive*
