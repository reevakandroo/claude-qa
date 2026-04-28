# TC094: PHI is not stored as plain text in browser localStorage

| Field | Detail |
|-------|--------|
| **Test ID** | TC094 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill patient form with unique data: PT-HIPAA-TEST |
| 2 | Open dev tools > Application > Local Storage |
| 3 | Search for PT-HIPAA-TEST |

## Expected Results

Patient ID and name do not appear in localStorage. PHI is not persisted in the browser in plain text.

---
*Module: HIPAA Compliance · Type: Positive*
