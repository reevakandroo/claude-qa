# TC022: ECG list scrolls smoothly with many entries — Scalability

| Field | Detail |
|-------|--------|
| **Test ID** | TC022 |
| **Module** | ECG Dashboard |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC004**](../00_preconditions/PC004_ecg_list_visible_with_entries.md) — ECG list is loaded with at least one entry visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Log in |
| 2 | Wait for ECG list |
| 3 | Scroll down to the bottom of the list |
| 4 | Scroll back up rapidly |
| 5 | Repeat 3 times |

## Expected Results

List scrolls smoothly. No freeze, no blank items, no crash during scrolling.

---
*Module: ECG Dashboard · Type: Edge*
