# TC039: Decimal age (1.5) is rejected

| Field | Detail |
|-------|--------|
| **Test ID** | TC039 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter Age: 1.5 |
| 2 | Fill other required fields |
| 3 | Observe risk button |

## Expected Results

Decimal age is rejected by the number input. Risk button stays disabled.

---
*Module: Patient Details Form · Type: Edge*
