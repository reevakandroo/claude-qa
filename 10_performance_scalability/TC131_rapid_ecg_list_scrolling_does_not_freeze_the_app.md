# TC131: Rapid ECG list scrolling does not freeze the app

| Field | Detail |
|-------|--------|
| **Test ID** | TC131 |
| **Module** | Performance & Scalability |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC004**](../00_preconditions/PC004_ecg_list_visible_with_entries.md) — ECG list is loaded with at least one entry visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Scroll down the ECG list rapidly 5 times |
| 2 | Scroll back up rapidly |
| 3 | Observe app responsiveness |

## Expected Results

List scrolls without frame drops or freezing. App remains fully interactive after scrolling.

---
*Module: Performance & Scalability · Type: Edge*
