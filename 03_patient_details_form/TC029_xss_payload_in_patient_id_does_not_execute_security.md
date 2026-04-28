# TC029: XSS payload in Patient ID does not execute — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC029 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click Patient ID field |
| 2 | Type: "><img src=x onerror=alert(1)> |
| 3 | Observe whether an alert fires |

## Expected Results

No JavaScript alert dialog appears. Input is treated as plain text. App remains stable.

---
*Module: Patient Details Form · Type: Edge*
