# TC127: Risk assessment result appears within 60 seconds

| Field | Detail |
|-------|--------|
| **Test ID** | TC127 |
| **Module** | Performance & Scalability |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Start timer when Get Risk Assessment is clicked |
| 2 | Wait for result to appear |
| 3 | Stop timer |

## Expected Results

Risk result is displayed within 60 seconds. A loading indicator is shown during the wait.

---
*Module: Performance & Scalability · Type: Positive*
