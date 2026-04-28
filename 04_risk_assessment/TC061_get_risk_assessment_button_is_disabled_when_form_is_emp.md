# TC061: Get Risk Assessment button is disabled when form is empty

| Field | Detail |
|-------|--------|
| **Test ID** | TC061 |
| **Module** | Risk Assessment |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open fresh patient form |
| 2 | Do not fill any field |
| 3 | Inspect the Get Risk Assessment button state |

## Expected Results

Button is visually disabled and cannot be clicked. No API call is made with empty fields.

---
*Module: Risk Assessment · Type: Negative*
