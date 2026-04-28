# TC040: Non-numeric text in Age field is not accepted

| Field | Detail |
|-------|--------|
| **Test ID** | TC040 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click Age field |
| 2 | Type the word: twenty |
| 3 | Observe the field value |

## Expected Results

Non-numeric characters are not accepted. Field remains empty or the input is stripped. No crash.

---
*Module: Patient Details Form · Type: Edge*
