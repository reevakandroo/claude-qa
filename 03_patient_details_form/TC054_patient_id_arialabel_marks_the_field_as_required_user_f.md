# TC054: Patient ID aria-label marks the field as required — User Friendliness

| Field | Detail |
|-------|--------|
| **Test ID** | TC054 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open patient form |
| 2 | Inspect the aria-label attribute on the Patient ID input |

## Expected Results

Aria-label contains an asterisk (*) or the word "required" indicating it is a mandatory field.

---
*Module: Patient Details Form · Type: Positive*
