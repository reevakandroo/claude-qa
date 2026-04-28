# TC035: Age of 151 (one above maximum) is rejected

| Field | Detail |
|-------|--------|
| **Test ID** | TC035 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all fields with Age: 151 |
| 2 | Select a gender |
| 3 | Observe the risk button |

## Expected Results

Age 151 is rejected. Get Risk Assessment button remains disabled.

---
*Module: Patient Details Form · Type: Edge*
