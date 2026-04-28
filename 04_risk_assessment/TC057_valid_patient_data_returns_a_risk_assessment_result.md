# TC057: Valid patient data returns a risk assessment result

| Field | Detail |
|-------|--------|
| **Test ID** | TC057 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill Patient ID: PT1001, Name: John Smith, Age: 55, Gender: Male |
| 2 | Click Get Risk Assessment |
| 3 | Wait for result |

## Expected Results

A risk level result is displayed on the page. The result is one of: Low, Moderate, or High.

---
*Module: Risk Assessment · Type: Positive*
