# TC063: Risk value is never outside the three valid categories

| Field | Detail |
|-------|--------|
| **Test ID** | TC063 |
| **Module** | Risk Assessment |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC006**](../00_preconditions/PC006_fresh_ecg_open_patient_form.md) — A New ECG is open; patient details form is displayed with all fields editable

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Fill patient details with varied inputs |
| 2 | Run assessment |
| 3 | Inspect the result text for any unexpected value |

## Expected Results

Result is always one of Low, Moderate, or High. No null, undefined, or unexpected string appears.

---
*Module: Risk Assessment · Type: Edge*
