# TC085: Script injection in patient name does not execute

| Field | Detail |
|-------|--------|
| **Test ID** | TC085 |
| **Module** | Security |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter <img src=x onerror=alert(document.cookie)> in Patient Name |
| 2 | Observe the page |

## Expected Results

No alert dialog fires. Cookie is not exposed. Script is not executed.

---
*Module: Security · Type: Edge*
