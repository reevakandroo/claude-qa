# TC044: Patient Name is optional — form valid without it

| Field | Detail |
|-------|--------|
| **Test ID** | TC044 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill Patient ID, Age, and Gender |
| 2 | Leave Patient Name completely empty |
| 3 | Observe the Get Risk Assessment button |

## Expected Results

Risk Assessment button is enabled even with empty Patient Name. Name field is not blocking submission.

---
*Module: Patient Details Form · Type: Positive*
