# TC047: Empty Age keeps risk button disabled

| Field | Detail |
|-------|--------|
| **Test ID** | TC047 |
| **Module** | Patient Details Form |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill Patient ID, Patient Name, and Gender |
| 2 | Leave Age empty |
| 3 | Observe the Get Risk Assessment button |

## Expected Results

Risk Assessment button remains disabled.

---
*Module: Patient Details Form · Type: Negative*
