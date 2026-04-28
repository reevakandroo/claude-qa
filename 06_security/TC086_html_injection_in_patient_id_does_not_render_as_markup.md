# TC086: HTML injection in Patient ID does not render as markup

| Field | Detail |
|-------|--------|
| **Test ID** | TC086 |
| **Module** | Security |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Enter <b>Bold</b> in Patient ID |
| 2 | Observe whether the text renders as bold HTML or as a plain string |

## Expected Results

Text is rendered as plain text: <b>Bold</b>. It does not render as bold HTML. No HTML injection.

---
*Module: Security · Type: Edge*
