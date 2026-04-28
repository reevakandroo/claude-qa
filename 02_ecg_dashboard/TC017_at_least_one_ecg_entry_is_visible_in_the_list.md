# TC017: At least one ECG entry is visible in the list

| Field | Detail |
|-------|--------|
| **Test ID** | TC017 |
| **Module** | ECG Dashboard |
| **Type** | ✅ Positive |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC004**](../00_preconditions/PC004_ecg_list_visible_with_entries.md) — ECG list is loaded with at least one entry visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in with valid credentials |
| 2 | Wait for dashboard |
| 3 | Count the number of ECG entries displayed in the list |

## Expected Results

At least one ECG entry is visible. The list is not empty.

---
*Module: ECG Dashboard · Type: Positive*
