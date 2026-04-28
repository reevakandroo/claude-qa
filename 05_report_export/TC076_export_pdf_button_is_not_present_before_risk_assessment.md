# TC076: Export PDF button is NOT present before risk assessment is run

| Field | Detail |
|-------|--------|
| **Test ID** | TC076 |
| **Module** | Report Export |
| **Type** | ❌ Negative |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open a fresh ECG |
| 2 | Observe the patient form screen |
| 3 | Look for the Export PDF button before clicking Get Risk Assessment |

## Expected Results

Export PDF button is NOT visible on the patient form screen. It only appears after a successful assessment.

---
*Module: Report Export · Type: Negative*
