# TC026: Patient ID of 6 to 12 alphanumeric characters is accepted

| Field | Detail |
|-------|--------|
| **Test ID** | TC026 |
| **Module** | Patient Details Form |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click the Patient ID field |
| 2 | Type PT1001 (6 characters) |
| 3 | Observe the field |
| 4 | Repeat with ABCD123456789 (13 chars) as a separate test |

## Expected Results

6-character ID: accepted and stored. 13-character ID: rejected or truncated to 12 characters. No crash on either attempt.

---
*Module: Patient Details Form · Type: Positive*
