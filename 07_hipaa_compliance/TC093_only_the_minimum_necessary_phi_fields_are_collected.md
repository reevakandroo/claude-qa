# TC093: Only the minimum necessary PHI fields are collected

| Field | Detail |
|-------|--------|
| **Test ID** | TC093 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Open patient form |
| 2 | Count and list all input fields present |
| 3 | Verify no excessive personal information is requested |

## Expected Results

Form collects only: Patient ID, Patient Name (optional), Age, Gender. No SSN, date of birth, address, phone number, or other excessive fields are present.

---
*Module: HIPAA Compliance · Type: Positive*
