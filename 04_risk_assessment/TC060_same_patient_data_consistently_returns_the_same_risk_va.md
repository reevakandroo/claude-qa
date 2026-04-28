# TC060: Same patient data consistently returns the same risk value

| Field | Detail |
|-------|--------|
| **Test ID** | TC060 |
| **Module** | Risk Assessment |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter the same patient data twice in two separate assessments |
| 2 | Compare both results |

## Expected Results

Both assessments return the same risk level for identical input data. Result is deterministic.

---
*Module: Risk Assessment · Type: Positive*
