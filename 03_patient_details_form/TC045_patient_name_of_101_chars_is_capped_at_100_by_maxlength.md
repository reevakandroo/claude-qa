# TC045: Patient name of 101+ chars is capped at 100 by maxLength — User Friendliness

| Field | Detail |
|-------|--------|
| **Test ID** | TC045 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click Patient Name field |
| 2 | Type a string of 110 characters (e.g. 110 letter As) |
| 3 | Observe the stored value length |

## Expected Results

Field accepts a maximum of 100 characters. Characters beyond 100 are not entered or are truncated. Stored value length is <= 100.

---
*Module: Patient Details Form · Type: Edge*
