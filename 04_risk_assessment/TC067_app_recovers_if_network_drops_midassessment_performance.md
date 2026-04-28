# TC067: App recovers if network drops mid-assessment — Performance / User Friendliness

| Field | Detail |
|-------|--------|
| **Test ID** | TC067 |
| **Module** | Risk Assessment |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill patient form |
| 2 | Click Get Risk Assessment |
| 3 | Immediately simulate offline mode (disable network) |
| 4 | Re-enable network after 2 seconds |

## Expected Results

App either shows a user-friendly error message or retries automatically. App does not freeze or crash. UI remains responsive.

---
*Module: Risk Assessment · Type: Edge*
