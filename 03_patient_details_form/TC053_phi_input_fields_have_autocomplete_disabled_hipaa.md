# TC053: PHI input fields have autocomplete disabled — HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC053 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open patient form |
| 2 | Inspect the autocomplete attribute on Patient ID, Patient Name, and Age input fields using dev tools |

## Expected Results

All PHI input fields have autocomplete set to "off" or are absent. Browser does not suggest previously entered patient data.

---
*Module: Patient Details Form · Type: Positive*
