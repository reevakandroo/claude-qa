# TC130: App handles navigation through 3 ECGs without performance degradation

| Field | Detail |
|-------|--------|
| **Test ID** | TC130 |
| **Module** | Performance & Scalability |
| **Type** | ⚠️ Edge |
| **Status** | ⬜ Pending |

## Preconditions

- [**PC004**](../00_preconditions/PC004_ecg_list_visible_with_entries.md) — ECG list is loaded with at least one entry visible

## Execution Steps

| Step | Action |
|------|--------|
| 1 | Click the first ECG |
| 2 | Navigate back |
| 3 | Click the second ECG |
| 4 | Navigate back |
| 5 | Click the third ECG |
| 6 | Observe speed and stability |

## Expected Results

Each ECG opens in a reasonable time. App does not slow down, freeze, or crash across multiple navigations.

---
*Module: Performance & Scalability · Type: Edge*
