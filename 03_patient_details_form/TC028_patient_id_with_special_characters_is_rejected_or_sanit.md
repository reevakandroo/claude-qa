# TC028: Patient ID with special characters is rejected or sanitised — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC028 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click Patient ID field |
| 2 | Type: '; DROP TABLE patients; -- |
| 3 | Fill other fields |
| 4 | Click Get Risk Assessment if enabled |

## Expected Results

App either rejects the input with a validation error or sanitises it. No SQL error is shown. No data corruption occurs.

---
*Module: Patient Details Form · Type: Edge*
