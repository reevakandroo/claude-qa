# TC124: User-friendly error shown when risk assessment API fails

| Field | Detail |
|-------|--------|
| **Test ID** | TC124 |
| **Module** | User Friendliness |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Disable network or trigger a server error |
| 2 | Click Get Risk Assessment |
| 3 | Read the message shown |

## Expected Results

A friendly error message is shown such as "Unable to process assessment. Please try again." No raw error code or stack trace is visible.

---
*Module: User Friendliness · Type: Negative*
