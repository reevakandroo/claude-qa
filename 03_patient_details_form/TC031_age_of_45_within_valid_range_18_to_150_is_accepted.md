# TC031: Age of 45 (within valid range 18 to 150) is accepted

| Field | Detail |
|-------|--------|
| **Test ID** | TC031 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click the Age field |
| 2 | Type 45 |
| 3 | Observe whether the value is retained |

## Expected Results

Age field retains the value 45. No validation error. Value is ready to be submitted.

---
*Module: Patient Details Form · Type: Positive*
