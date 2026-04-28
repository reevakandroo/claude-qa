# TC030: XSS payload in Patient Name does not execute — Security

| Field | Detail |
|-------|--------|
| **Test ID** | TC030 |
| **Module** | Patient Details Form |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click Patient Name field |
| 2 | Type: <script>alert("xss")</script> |
| 3 | Observe the page |

## Expected Results

No alert fires. Script is not executed. Field shows the text as a literal string or rejects it.

---
*Module: Patient Details Form · Type: Edge*
