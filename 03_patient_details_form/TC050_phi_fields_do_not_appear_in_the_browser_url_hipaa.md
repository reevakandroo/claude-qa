# TC050: PHI fields do not appear in the browser URL — HIPAA

| Field | Detail |
|-------|--------|
| **Test ID** | TC050 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill Patient ID: PT-SECRET, Name: John Private, Age: 45, Gender: Male |
| 2 | Check the browser address bar |
| 3 | Note the URL |

## Expected Results

Patient ID, name, age, and gender do not appear as query parameters in the URL. PHI stays out of the address bar.

---
*Module: Patient Details Form · Type: Positive*
