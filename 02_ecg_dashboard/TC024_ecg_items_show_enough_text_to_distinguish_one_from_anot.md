# TC024: ECG items show enough text to distinguish one from another — User Friendliness

| Field | Detail |
|-------|--------|
| **Test ID** | TC024 |
| **Module** | ECG Dashboard |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC004**](../00_preconditions/PC004_ecg_list_visible_with_entries.md) — ECG list is loaded with at least one entry visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in |
| 2 | Wait for ECG list |
| 3 | Read the text displayed on each ECG entry card |
| 4 | Check whether entries look identical or distinct |

## Expected Results

Each ECG entry displays distinguishing information (e.g. patient ID, date, or status). Entries are not all blank or identical.

---
*Module: ECG Dashboard · Type: Positive*
