# TC034: Age of 17 (one below minimum) is rejected

| Field | Detail |
|-------|--------|
| **Test ID** | TC034 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all fields with Age: 17 |
| 2 | Select a gender |
| 3 | Observe the risk button and any validation message |

## Expected Results

Age 17 is rejected. Get Risk Assessment button remains disabled. Validation message shows the acceptable range (18-150).

---
*Module: Patient Details Form · Type: Edge*
