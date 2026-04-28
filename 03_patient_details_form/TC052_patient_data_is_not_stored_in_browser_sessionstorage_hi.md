# TC052: Patient data is not stored in browser sessionStorage — HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC052 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all patient fields with unique values |
| 2 | Open browser dev tools > Application > Session Storage |
| 3 | Search for the entered values |

## Expected Results

Patient data is not stored in sessionStorage as plain text.

---
*Module: Patient Details Form · Type: Positive*
