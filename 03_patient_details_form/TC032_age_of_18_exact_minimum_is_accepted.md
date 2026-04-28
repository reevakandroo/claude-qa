# TC032: Age of 18 (exact minimum) is accepted

| Field | Detail |
|-------|--------|
| **Test ID** | TC032 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all fields with Age: 18 |
| 2 | Select a gender |
| 3 | Observe the Get Risk Assessment button |

## Expected Results

Age 18 is accepted. Risk Assessment button is enabled.

---
*Module: Patient Details Form · Type: Edge*
