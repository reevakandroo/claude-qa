# TC095: PHI is not stored as plain text in browser sessionStorage

| Field | Detail |
|-------|--------|
| **Test ID** | TC095 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill patient form |
| 2 | Open dev tools > Application > Session Storage |
| 3 | Search for entered patient values |

## Expected Results

No patient identifiers are stored in sessionStorage as readable plain text.

---
*Module: HIPAA Compliance · Type: Positive*
