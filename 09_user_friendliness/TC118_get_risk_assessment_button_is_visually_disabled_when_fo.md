# TC118: Get Risk Assessment button is visually disabled when form is incomplete

| Field | Detail |
|-------|--------|
| **Test ID** | TC118 |
| **Module** | User Friendliness |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open patient form |
| 2 | Fill only some fields (e.g. name only) |
| 3 | Observe the Get Risk Assessment button appearance |

## Expected Results

Button appears greyed out or visually distinct to indicate it is not clickable. User understands action is not yet possible.

---
*Module: User Friendliness · Type: Positive*
