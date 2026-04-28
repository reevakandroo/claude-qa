# TC036: Age of 0 is rejected

| Field | Detail |
|-------|--------|
| **Test ID** | TC036 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter Age: 0 |
| 2 | Fill other required fields |
| 3 | Observe risk button |

## Expected Results

Age 0 is rejected as below minimum. Risk button stays disabled.

---
*Module: Patient Details Form · Type: Edge*
