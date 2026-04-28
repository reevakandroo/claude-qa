# TC048: No gender selected keeps risk button disabled

| Field | Detail |
|-------|--------|
| **Test ID** | TC048 |
| **Module** | Patient Details Form |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill Patient ID, Patient Name, and Age |
| 2 | Do not select a Gender |
| 3 | Observe the button |

## Expected Results

Risk Assessment button remains disabled. Gender is a required field.

---
*Module: Patient Details Form · Type: Negative*
