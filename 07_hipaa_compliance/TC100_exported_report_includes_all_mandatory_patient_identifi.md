# TC100: Exported report includes all mandatory patient identifiers

| Field | Detail |
|-------|--------|
| **Test ID** | TC100 |
| **Module** | HIPAA Compliance |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC007**](../00_preconditions/PC007_full_workflow_completed.md) — Login → ECG open → form filled → assessment run → result shown → Export PDF visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Complete assessment with known patient data |
| 2 | Click Export PDF |
| 3 | Open the PDF or preview |
| 4 | Verify patient name, ID, age, gender, and risk level are all present |

## Expected Results

Exported report contains all of: Patient ID, Patient Name, Age, Gender, Risk Level. No mandatory field is blank.

---
*Module: HIPAA Compliance · Type: Positive*
