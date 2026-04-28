# TC049: All fields empty keeps risk button disabled

| Field | Detail |
|-------|--------|
| **Test ID** | TC049 |
| **Module** | Patient Details Form |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open a fresh patient form |
| 2 | Do not fill any field |
| 3 | Observe the Get Risk Assessment button immediately |

## Expected Results

Risk Assessment button is disabled by default when no fields are filled.

---
*Module: Patient Details Form · Type: Negative*
