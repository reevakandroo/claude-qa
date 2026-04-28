# TC025: All valid fields filled enables the Get Risk Assessment button

| Field | Detail |
|-------|--------|
| **Test ID** | TC025 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open a New ECG |
| 2 | Enter Patient ID: PT1001 |
| 3 | Enter Patient Name: John Doe |
| 4 | Enter Age: 45 |
| 5 | Select Gender: Male |
| 6 | Observe the Get Risk Assessment button state |

## Expected Results

Get Risk Assessment button becomes enabled (clickable). All fields show no validation errors.

---
*Module: Patient Details Form · Type: Positive*
