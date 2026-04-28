# TC123: Loading state is shown during risk assessment API call

| Field | Detail |
|-------|--------|
| **Test ID** | TC123 |
| **Module** | User Friendliness |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all patient fields |
| 2 | Click Get Risk Assessment |
| 3 | Observe the screen immediately after clicking |

## Expected Results

A loading indicator (spinner, progress bar, or disabled button) is shown while waiting for the API response. User knows the app is working.

---
*Module: User Friendliness · Type: Positive*
