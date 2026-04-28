# TC027: Patient ID shorter than 6 characters keeps risk button disabled

| Field | Detail |
|-------|--------|
| **Test ID** | TC027 |
| **Module** | Patient Details Form |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click Patient ID field |
| 2 | Type PT1 (3 characters — below minimum) |
| 3 | Fill all other fields correctly |
| 4 | Observe the Get Risk Assessment button |

## Expected Results

Get Risk Assessment button remains disabled. Validation error hints the minimum length requirement.

---
*Module: Patient Details Form · Type: Negative*
