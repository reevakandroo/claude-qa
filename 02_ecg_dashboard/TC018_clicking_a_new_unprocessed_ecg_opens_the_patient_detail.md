# TC018: Clicking a new unprocessed ECG opens the patient detail form

| Field | Detail |
|-------|--------|
| **Test ID** | TC018 |
| **Module** | ECG Dashboard |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC005**](../00_preconditions/PC005_unprocessed_ecg_available.md) — At least one New ECG entry exists in the list

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in |
| 2 | Identify an ECG entry labelled New ECG in the list |
| 3 | Click on it |
| 4 | Wait for the next screen to load |

## Expected Results

Patient detail form opens showing input fields for Patient ID, Patient Name, Age, and Gender. Form is editable.

---
*Module: ECG Dashboard · Type: Positive*
