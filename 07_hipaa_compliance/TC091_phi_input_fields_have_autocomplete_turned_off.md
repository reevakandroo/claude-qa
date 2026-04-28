# TC091: PHI input fields have autocomplete turned off

| Field | Detail |
|-------|--------|
| **Test ID** | TC091 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open patient form |
| 2 | Inspect autocomplete attribute on Patient ID, Patient Name, and Age |
| 3 | Check if browser suggests previous values |

## Expected Results

Autocomplete is set to "off" on all PHI fields. Browser does not pre-fill patient data from history.

---
*Module: HIPAA Compliance · Type: Positive*
