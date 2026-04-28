# TC062: Double-clicking Get Risk Assessment is handled gracefully — Scalability

| Field | Detail |
|-------|--------|
| **Test ID** | TC062 |
| **Module** | Risk Assessment |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill all valid patient fields |
| 2 | Double-click the Get Risk Assessment button rapidly |
| 3 | Observe whether two API calls are made or app crashes |

## Expected Results

App handles the double-click gracefully. Either only one assessment is requested or the second click is ignored. App does not crash.

---
*Module: Risk Assessment · Type: Edge*
