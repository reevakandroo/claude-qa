# TC088: Patient data does not appear in browser URL after form fill

| Field | Detail |
|-------|--------|
| **Test ID** | TC088 |
| **Module** | Security |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all patient fields |
| 2 | Click Get Risk Assessment |
| 3 | Check the browser URL at every step |

## Expected Results

Patient name, ID, age, and gender do not appear as URL query parameters at any point.

---
*Module: Security · Type: Positive*
